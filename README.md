# What is it? 
A base project that in the future should be exactly what it's called. Kinda local, via WebSockets, simple interface.

# How to build
## 1. Fetch deps (git clones ImGui/ImPlot/sol2/json, apt-installs the rest)
<pre>
./scripts/setup_deps.sh
</pre>
## 2. Build
<pre>
cmake -B build -DCMAKE_BUILD_TYPE=Release
cmake --build build -j$(nproc)
</pre>
## 3. Run
<pre>
./build/kindaLikeTigerButNot
</pre>
## 4. AppImage
<pre>
cmake --build build --target appimage
</pre>

→ kindaLikeTigerButNot-1.0.0-x86_64.AppImage


# Interface
![Main Interface](/resources/kltbn_main_interface.png)
![Chart Interface](/resources/kltbn_chart_interface.png)
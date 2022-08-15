# simple-text-editor

### Installation
 
1. Clone the repo
   ```sh
   git clone https://github.com/ispectr/simple-text-editor.git
   ```
2. Install.
   ```sh
   mkdir build && cd build
   cmake .. -DCMAKE_INSTALL_PREFIX=$HOME/.local-kde
   make install
   source prefix.sh # located in the build directory
   ```
3. Run.
   ```sh
   texteditor
   ```

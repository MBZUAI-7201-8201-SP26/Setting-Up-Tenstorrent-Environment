## Setting up Tenstorrent Environment

*Some of the steps here are covered in the Lab 1 instructions as well.*

1. Clone `tt-metal`:

   ```
   git clone https://github.com/tenstorrent/tt-metal.git --recurse-submodules
   ```

1. Build `tt-metal`:

   ```
   cd ./tt-metal
   ./build_metal.sh
   ```

1. Create the Python environment:

   ```
   ./create_venv.sh
   ```

1. Remember to activate the python environment so as to use the Tenstorrent software stacks:

   ```
   source python_env/bin/activate
   ```

1. When you have the environment active, you can test out some of the Tenstorrent features:

  - `tt-smi`:
    
    ```
    tt-smi
    ```

  - `ttnn`:

    ```
    python3
    import ttnn
    ```
    

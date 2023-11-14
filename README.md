# pdiot-ml

<!-- ## Adding a Submodule
1. To add a submodule to your repository, navigate to your repository's root directory and use the following command:

   ```sh
   git submodule add <repository-url> <path-to-submodule>
   ```
   - `<repository-url>`: The URL of the submodule repository.
   - `<path-to-submodule>`: The path within your repository where the submodule should be placed.

   For example:
   ```sh
   git submodule add git@github.com:specknet/pdiot-data.git .
   ```

2. After adding the submodule, you'll see it listed in a `.gitmodules` file in your repository. You should add this file to your repository:

   ```sh
   git add .gitmodules
   git commit -m "Added submodule"
   ``` -->

When you clone a repository that contains submodules, you need to initialize and update the submodules. You can do this with a single command:

```sh
git clone --recurse-submodules git@github.com:YangSierCode000/pdiot-ml.git
```

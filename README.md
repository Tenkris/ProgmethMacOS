# ProgmethMacOS
setup tool in progmeth Class (For MacOS user) 

To install the latest version of OpenJDK using Homebrew on macOS, follow these steps:

### Step 1: Open Terminal
- You can find the Terminal in the Utilities folder within your Applications folder, or use Spotlight Search (`Cmd + Space`) to find it.

### Step 2: Install Homebrew (if not already installed)
- If Homebrew is not installed, run this command in the Terminal:

  ```bash
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```

- Follow the on-screen instructions to complete the installation.
- After installation, type `brew help` to verify that Homebrew is installed correctly.

### Step 3: Update Homebrew
- It's good practice to update Homebrew before installing new packages:

  ```bash
  brew update
  ```

### Step 4: Install the Latest Version of OpenJDK
- To install the latest version of OpenJDK, run this command:

  ```bash
  brew install openjdk
  ```

### Step 5: Verify the Java Installation
- After the installation is complete, verify it by typing:

  ```bash
  java -version
  ```

  This command will display the installed version of OpenJDK.
### Step6 : Optionally, you can set the `JAVA_HOME` environment variable to point to the OpenJDK installation directory. This step is useful if you want to use OpenJDK with other tools or frameworks that rely on the `JAVA_HOME` variable. To set the `JAVA_HOME` variable, run the following command:
   ```bash
   echo 'export JAVA_HOME="/usr/local/opt/openjdk"' >> ~/.zshrc
   ```

   This command appends the `export JAVA_HOME="/usr/local/opt/openjdk"` line to your `.zshrc` file.

### Step7 : To apply the changes made to the `.zshrc` file, either restart your terminal or run the following command:
   ```bash
   source ~/.zshrc
   ```

Now, OpenJDK is successfully installed on your macOS system using Homebrew. You can use it for your Java development needs.



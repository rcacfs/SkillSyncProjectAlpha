# steps to Create Feature Branch

## 1. Clone the Repository

1. Opened Git Bash terminal.
2. Navigated to the directory where I wanted to clone the repository.
3. I ran the following command to clone the repository:

    ```sh
        git clone https://github.com/rcacfs/SkillSyncProjectAlpha.git
            ```


  https://github.com/rcacfs/SkillSyncProjectAlpha/blob/feature/wachiye/images/clone%20repo.png
  
## 2. Checkout to Development Branch

1. I changed my directory to the cloned repository:

    ```sh
        cd SkillSyncProjectAlpha
            ```
2. I checked out to the development branch:

    ```sh
        git checkout development
            ```
## 3. Create a Feature Branch

1. I created a new feature branch, replacing `your_surname` with my actual surname:

    ```sh
        git checkout -b feature/wachiye
            ```

## 4. Verify I am on My Feature Branch

1. I verified that I successfully checked out to my feature branch:

    ```sh
        git branch
            ```
        The command returned `* feature/wachiye` indicating that I was on the feature branch.

## 5. Create a .md File Named wachiye.md

1. I created a new Markdown file.


    ```sh
        touch  wachiye.md
            ```

2. I opened this file in a text editor and added the steps I used to create the feature branch.

    ```sh
        vim wachiye.md
    

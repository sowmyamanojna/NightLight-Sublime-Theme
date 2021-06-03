# Night Light - Theme and Color Scheme
Color Scheme - A refreshingly new color scheme that looks good with Night Light enabled.

Theme - A mix of the good from the official sublime theme and [Sublime Meetio theme](https://github.com/meetio-theme/sublime-meetio-theme), with some additions.  

In order to activate the theme and color scheme:

1. Navigate to the `.config/subime-text/Packages/` folder using: 
    ```bash
    cd /home/<user-name>/.config/sublime-text/Packages/
    ```
2. Clone this git repository in the current folder using:
    ```bash
    git clone https://github.com/sowmyamanojna/Sublime-Theme.git
    ```
3. Check if the `Theme - Default/` folder exists:
    - If the folder doesn't exist, create the folder and move the Night Light theme into the folder.
        ```bash
        mkdir Theme\ -\ Default/
        mv Sublime-Theme/ Theme\ -\ Default/nightlight
        ```
    - Else, move the Night Light theme into the `Theme - Default/` folder.
        ```bash
        mv Sublime-Theme/ Theme\ -\ Default/nightlight
        ```
4. In order to activate the nightlight color scheme, navigate back to the `.config/subime-text/Packages/` folder and check if the `Color Scheme - Default` folder exists.
    - If the folder doesn't exist, create the folder and move the nightlight color scheme into the folder.
        ```bash
        mkdir Color\ Scheme\ -\ Default/
        ```
    - Else, move the Night Light color scheme into the `Color Scheme - Default/` folder.
5. In order to have better icons, install the `A File Icon` package.
6. Now the Night Light theme is set up. :smile:
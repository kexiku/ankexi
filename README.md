# <p align="center"> <b> :blueberries: Ankexi :blueberries: </b> </p>

<p align="center">
  <img src="/assets/preview.webp" alt="Flash card preview" />
</p>

> [!NOTE]
> This project is a fork of [Ankite](https://github.com/Swiddis/Ankite) by Simeon Widdis

*Ankexi* is a minimalist Anki template suitable for English vocabulary flashcards.

While I maintain this project primarily for personal use, I'd be happy if it found a place in your tool belt and bring some flair to your study routine :white_heart:

As the original creator states:
> *...it's designed mostly with language learning in mind, but at a glance there shouldn't be much in the way of using it for other subjects*

### :star: Core features
- Adjustable color schemes
- Dark & light mode compatibility
- Mobile support

### :sparkles: Fork enhancements

- More color schemes
- Extended note types support
- Aesthetic wallpapers included

## :hammer_and_wrench: Installation

You have 2 options:

### :package: Ready-made

Standard card pack.  
Includes basic, cloze and ru15k sentence decks, alongside with the default one.

To use it, go to release page, download the `.apkg` file and import to your collection.

> [!IMPORTANT]
> I couldn't find a way to get Anki to include wallpaper files in the archive, so for now, the best workaround is to manually download the wallpapers folder and place it in `collection.media` inside your profile folder.
>
> [*How to locate the profile folder?*](https://docs.ankiweb.net/files.html#user-data)

### :sewing_needle: Handmade

Template files you can manually add to your cards and customize as you wish :cherry_blossom:

<details>
  <summary>HTML & CSS</summary><br/>

  - Find source files [here](/templates)
  - Open 'Manage Note Types' (`Ctrl` + `Shift` + `N`), then 'Cards', and copy-paste the code from each template file to the corresponding field
</details>

<details>
  <summary>Fields</summary><br/>

  If you'd like to implement the same card type I use, go to 'Manage Note Types', click 'Add', 'Add: Cloze', and edit the card fields as follows:

  ```shell
  1. Word
  2. Audio
  3. Pronunciation
  4. Definition
  5. Example # rename 'Text' to this one
  ```

  Make sure the default 'Text' field is using as an 'Example' one, otherwise it won't allow you to create cloze deletions.
</details>

<details>
  <summary>Font</summary><br/>

  - Locate font files [here](./fonts)
  - Follow the [Anki Manual on Installing Fonts](https://docs.ankiweb.net/templates/styling.html#installing-fonts)
</details>

<details>
  <summary>Wallpapers</summary><br/>

  - Move the [wallpapers](./wallpapers) folder to your Anki profile directory (`%APPDATA%\Anki2` on Windows)  
  - Your styling template should automatically load the correct wallpaper then
</details>

## :framed_picture: Overview

### <p align="center"> <i> · Light themes · </i> </p>

<p align="center">
  <a><img src="./assets/screenshots/blueberry.yoghurt.webp" width="48%" alt="blueberry yoghurt theme preview" /></a>
  <a><img src="./assets/screenshots/catppuccin.latte.webp" width="48%" alt="catppuccin latte theme preview" /></a>
</p>
<p align="center">
  <a><img src="./assets/screenshots/everforest.webp" width="48%" alt="everforest theme preview" /></a>
  <a><img src="./assets/screenshots/rose.pine.dawn.webp" width="48%" alt="rosé pine dawn theme preview" /></a>
</p>

### <p align="center"> <i> · Dark themes · </i> </p>

<p align="center">
  <a><img src="./assets/screenshots/catppuccin.macchiato.webp" width="48%" alt="catppuccin macchiato theme preview" /></a>
  <a><img src="./assets/screenshots/kanagawa.webp" width="48%" alt="kanagawa theme preview" /></a>
</p>
<p align="center">
  <a><img src="./assets/screenshots/nord.webp" width="48%" alt="nord theme preview" /></a>
  <a><img src="./assets/screenshots/piano.woman.webp" width="48%" alt="piano woman theme preview" /></a>
</p>

<p align="center">
  <i> All the available theme templates can be found <a href="./templates/color%20schemes/">here</a> </i>
</p>

## :scroll: License

This project is licensed under the MIT license, see [`LICENSE`](./LICENSE) for details.  
The [Literata](https://github.com/googlefonts/literata) font used in this project is licensed under the OFL-1.1 license.

If you want to see your favorite deck supported, or having trouble with one of the existing ones, feel free to open an issue or contact me directly by email: [kexiku@proton.me](mailto:kexiku@proton.me)

### <p align="center"> 𓆩♡𓆪 </p>

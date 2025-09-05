# 🎥 Dynamo

<center>
<img src="./Dynamo%20Desktop/Assets/Images/Dynamo.png" alt="Dynamo Logo" width="100%" />
</center>

> [!WARNING]
> - This application is intended for educational and personal use only. Please ensure you have the right to access and stream the content you choose to view.
> - The developers of Dynamo are not responsible for any legal issues arising from the use of this application. Always use legal and ethical means to access content.
> - Please respect copyright laws and the rights of content creators.

## Overview
🚀 Dynamo is a cross-platform application for streaming anime from external sources. It uses media players like MPV and VLC to provide a seamless viewing experience.

> [!NOTE]
> - Dynamo is not affiliated with any anime streaming services. It simply provides a way to access publicly available content through supported sources.
> - Some sources may have regional restrictions or require a subscription for access. Please ensure you comply with the terms of service of each source.
> - The availability of sources may change over time, and some sources may become unavailable or unsupported.
> - Always use the latest version of Dynamo to ensure compatibility with supported sources.
> - A list of changes and updates can be found in the [CHANGELOG](./CHANGELOG.md).

## ✨ Features

- 📺 Stream anime from various sources  
- 🎛️ Support for multiple media players *(MPV, VLC)*  
- 💻 Cross-platform *(Windows, macOS, Linux)*  
- 🛠️ User-friendly interface  
- 🔄 Regular updates and improvements  

## Screenshots

<center>
<img src="./Dynamo%20Desktop/Assets/Images/Screenshots/Screenshot%20(2).png" alt="Main Window" width="100%" />
<p align="center">Browse through hundreds of popular anime</p>
<br />
<img src="./Dynamo%20Desktop/Assets/Images/Screenshots/Screenshot%20(3).png" alt="Anime List" width="100%" />
<p align="center">Stream your favorite anime using external media players like VLC and MPV</p>
</center>

## 📚 Sources

> [!NOTE]
> - Sources marked with ✅ are currently supported in Dynamo.
> - Sources marked with ❌ are not currently supported but *may* be added in future updates.
> - If you have a specific source you'd like to see supported, feel free to open an issue or submit a pull request!

### Anime

| Source Name | Source URL | Status |
|-------------|---------|---------|
| GoGoAnime | [https://gogoanime.pe/](https://gogoanime.pe/) | ✅ |
| ZoroAnime | [https://zoro.to/](https://zoro.to/) | ✅ |
| AnimePahe | [https://animepahe.com/](https://animepahe.com/) | ✅ |
| 9AnimeTV | [https://9animetv.to/](https://9animetv.to/) | ❌ |
| MyAnimeList | [https://myanimelist.net/](https://myanimelist.net/) | ❌ |
| AniList | [https://anilist.co/](https://anilist.co/) | ❌ |
| Crunchyroll | [https://crunchyroll.com/](https://crunchyroll.com/) | ❌ |
| Funimation | [https://funimation.com/](https://funimation.com/) | ❌ |
| HIDIVE | [https://hidive.com/](https://hidive.com/) | ❌ |
| Anime Planet | [https://www.anime-planet.com/](https://www.anime-planet.com/) | ❌ |
| AnimeKai | [https://animekai.to/](https://animekai.to/) | ❌ |

### Hentai

> [!WARNING]
> - Hentai content is intended for adults only. Please ensure you are of legal age in your jurisdiction before accessing such content.
> - Some sources may contain explicit content. Viewer discretion is advised.

| Source Name | Source URL | Status |
|-------------|---------|---------|
| hanime | [https://hanime.tv/](https://hanime.tv/) | ✅ |
| Hentai Haven | [https://hentaihaven.xxx/](https://hentaihaven.xxx/) | ❌ |
| Rule34Video | [https://rule34video.com/](https://rule34video.com/) | ❌ |
| Simply Hentai | [https://www.simply-hentai.com/](https://www.simply-hentai.com/) | ❌ |

## 📥 Installation
To install and run Dynamo, follow the steps below:

### Prerequisites
Requirements vary based on whether you are using the pre-built executable or building from source.

#### If using the pre-built executable:

- [.NET Runtime](https://dotnet.microsoft.com/download) (Version 6.0 or later)
- [MPV](https://mpv.io/installation/) or [VLC](https://www.videolan.org/vlc/)

#### If building from source:

- [.NET SDK](https://dotnet.microsoft.com/download) (Version 6.0 or later)
- [Git](https://git-scm.com/)
- [MPV](https://mpv.io/installation/) or [VLC](https://www.videolan.org/vlc/)  

### Steps

#### Using Pre-built Executable (Recommended for Users)
The easiest way to get started with Dynamo is by using the pre-built executable.

1. Download the latest `.exe` file from the [releases page](https://github.com/SaverinOnRails/Dynamo/releases).  
2. Run the executable and follow the on-screen instructions.  

#### Building from Source (For Developers)
Developers and advanced users can build Dynamo from source.

1. Clone the repository:  
   ```sh
   git clone https://github.com/SaverinOnRails/Dynamo.git
   cd Dynamo
   ```

2. Restore dependencies:  
   ```sh
   dotnet restore
   ```
   
3. Build the project:  
   ```sh
   dotnet build
   ```

4. Run the application:  
   ```sh
   cd "Dynamo Desktop"
   dotnet run
   ```

### 📖 Usage
Once you have Dynamo installed and running, follow these steps to start streaming anime:

1. Open the application.  
2. Select a source *(e.g., Gogoanime, Animepahe)*.  
3. Browse or search for your favorite anime.  
4. Choose a media player *(MPV or VLC)* and start streaming.

### 🤝 Contributing
We welcome contributions from the community! Here’s how you can get involved:

1. Fork the repository.
2. Create a new branch *(git checkout -b feature-branch)*.
3. Make your changes.
4. Commit your changes *(git commit -m 'Add some feature')*.
5. Push to the branch *(git push origin feature-branch)*.
6. Open a pull request.

Please ensure your code adheres to the existing style and includes appropriate tests.

### 🐛 Reporting Issues
If you encounter any bugs or have feature requests, please open an issue on the [GitHub Issues page](https://github.com/SaverinOnRails/Dynamo/issues).

### 📜 License
Dynamo is licensed under the [MIT License](./LICENSE). Feel free to use, modify, and distribute the software as per the terms of the license.

### 🙏 Contributors
Thanks to all the contributors who have helped make Dynamo better!

| Name        | Role    |
|-------------|---------|
| [SaverinOnRails](https://github.com/SaverinOnRails) | Creator and maintainer of Dynamo. |
| [The Back Room](https://the-back-room.info) | Minor updates and improvements. |
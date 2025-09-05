# 🎥 Dynamo

![Dynamo Logo](./Dynamo%20Desktop/Assets/Images/Dynamo.png)

## Overview

🚀 Dynamo is a cross-platform application for streaming anime from external sources. It uses media players like MPV and VLC to provide a seamless viewing experience.

## ✨ Features

- 📺 Stream anime from various sources  
- 🎛️ Support for multiple media players *(MPV, VLC)*  
- 💻 Cross-platform *(Windows, macOS, Linux)*  
- 🛠️ User-friendly interface  
- 🔄 Regular updates and improvements  

## Screenshots

![Dynamo Screenshot](./Dynamo%20Desktop/Assets/Images/Screenshots/Screenshot%20(2).png)  
*1. Browse through hundreds of popular anime*  

![Dynamo Screenshot](./Dynamo%20Desktop/Assets/Images/Screenshots/Screenshot%20(3).png)  
*2. Stream your favorite anime using external media players like VLC and MPV*  

## 📚 Supported Sources

### Anime Sources

| Source Name | Website | Status |
|-------------|---------|---------|
| Gogoanime | [https://gogoanime.pe](https://gogoanime.pe) | ✅ |
| ZoroAnime | [https://zoro.to](https://zoro.to) | ✅ |
| Animepahe | [https://animepahe.com](https://animepahe.com) | ✅ |
| 9AnimeTV | [https://9animetv.to](https://9animetv.to) | ❌ |
| MyAnimeList | [https://myanimelist.net](https://myanimelist.net) | ❌ |
| AniList | [https://anilist.co](https://anilist.co) | ❌ |


### Hentai Sources

| Source Name | Website | Status |
|-------------|---------|---------|
| hAnime | [https://hanime.tv](https://hanime.tv) | ✅ |
| HentaiHaven | [https://hentaihaven.org](https://hentaihaven.org) | ❌ |
| Rule34Video | [https://rule34video.com](https://rule34video.com) | ❌ |


## 📥 Installation

### Prerequisites

- [.NET 6.0 Runtime](https://dotnet.microsoft.com/download/dotnet/6.0) or later *(if using the .exe version)*  
- [.NET SDK](https://dotnet.microsoft.com/download) *(if building from source)*
- [Git](https://git-scm.com/) *(if building from source)*
- [MPV](https://mpv.io/installation/) or [VLC](https://www.videolan.org/vlc/)  

### Steps

#### Using Pre-built Executable (Recommended for Users)

1. Download the latest `.exe` file from the [releases page](https://github.com/SaverinOnRails/Dynamo/releases).  
2. Run the executable and follow the on-screen instructions.  

#### Building from Source (For Developers)

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
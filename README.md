# React Music Player

This is a React music player that allows users to play and manage their favorite songs. It is built using React and styled with CSS.

## Features

- Play, pause, skip and rewind tracks
- Shuffle and repeat options
- Volume control
- Progress bar with time display
- Song list with search and filtering options
- Responsive design for mobile and desktop

## Installation

1. Clone the repository:

``` 
git clone https://github.com/Saiiru/react-music-player.git
```


2. Install dependencies:


3. Start the development server:


4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

To add your own songs, place the audio files in the `public` folder and update the `songs` array in `src/data.js` with the relevant information.

```javascript
export const songs = [
{
 title: "Song Title",
 artist: "Artist Name",
 cover: "/path/to/cover/image.jpg",
 file: "/path/to/audio/file.mp3"
},
// add more songs here
];

```

License

This project is licensed under the MIT License.

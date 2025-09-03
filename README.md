# Cyroni Bot

Cyroni is a Discord bot designed to provide music playback, utility commands, and audio filters for your server.

## Features

*   **Music Playback:**
    *   Play music from various sources (e.g., YouTube, Spotify).
    *   Queue management (add, remove, view queue).
    *   Playback controls (play, pause, resume, skip, stop, loop).
    *   Volume control.
    *   Autoplay functionality.
    *   Join and leave voice channels.
*   **Audio Filters:**
    *   Apply various audio filters like Bass Boost, Karaoke, Lofi, Nightcore, Vaporwave, Rotation, and Reset.
*   **Utility Commands:**
    *   Help command to list all available commands.
    *   Ping command to check bot latency.
    *   Server statistics and uptime.
    *   Invite command.
    *   Support command.
*   **Event Handling:**
    *   Tracks player start and end events.

## Setup Instructions

### Prerequisites

*   **Node.js:** Version 22.0.0 or higher. You can download it from [https://nodejs.org/](https://nodejs.org/).

### Installation

1.  **Clone the repository:**
    ``` unzip Cyroni.zip && bash
    git clone https://github.com/
    cd Cyroni
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Configure the bot:**
    *   Add your Discord bot token and any other necessary configurations (e.g., prefix, owner IDs). A basic `config.js` might look like this:
        ```javascript
        module.exports = {
            token: "YOUR_DISCORD_BOT_TOKEN",
            prefix: "!", // Or your preferred prefix
            ownerId: ["YOUR_USER_ID"], // Your Discord User ID
            // Add other configurations as needed
        };
        ```
4.  **Run the bot:**
    ```bash
    node index.js
    ```

## Thank You

# SupremeFriends - Minecraft Friend Plugin

![Version](https://img.shields.io/badge/version-1.0-brightgreen.svg)
![Java](https://img.shields.io/badge/java-1.8%2B-blue.svg)
![Spigot](https://img.shields.io/badge/spigot-1.17%2B-blue.svg)
![BungeeCord](https://img.shields.io/badge/bungeecord-1.17%2B-blue.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

SupremeFriends is a powerful and feature-rich friend management plugin for Minecraft servers. It enhances player interactions by providing a seamless friend system, friend requests, and BungeeCord integration.

## Features

- Easy-to-use friend commands for adding, removing, and managing friends.
- Friend requests with options to accept or deny incoming requests.
- Seamless integration with BungeeCord to check friend status across network servers.
- "Jump to Friend" feature to instantly teleport to your friend's server.
- Customizable settings to tailor the plugin to your server's preferences.
- Support for both Spigot and BungeeCord servers.
- Messages configuration for easy localization and customization.

## Commands

- `/friend accept <player>` - Accept a friend request.
- `/friend add <player>` - Send a friend request.
- `/friend best <player>` - Get the best friend of a player.
- `/friend deny <player>` - Deny a friend request.
- `/friend jump <friend>` - Teleport to a friend's server (BungeeCord).
- `/friend help` - Display the list of available commands.
- `/friend options` - Configure friend-related options.
- `/friend list / <friends/best>` - List your friends or best friends.
- `/friend remove <player>` - Remove a friend from your list.
- `/friend removeall` - Remove all friends.
- `/friend requests` - List pending friend requests.

## Installation

1. Download the latest plugin JAR from the [releases](https://github.com/yourusername/SupremeFriends/releases) page.
2. Place the JAR file into your server's `plugins` folder.
3. Restart or reload your server.
4. Configure the plugin settings in the `plugins/SupremeFriends/config.yml` file.
5. Customize messages in the `plugins/SupremeFriends/messages.yml` file.

## Configuration

The `config.yml` file in the `plugins/SupremeFriends` folder allows you to customize various aspects of the plugin, including BungeeCord integration and friend limits.

For detailed configuration options and explanations, please refer to the [Configuration Guide](docs/configuration.md).

## Messages

Customize the messages displayed by the plugin in the `messages.yml` file in the `plugins/SupremeFriends` folder.

For a list of available message placeholders and customization options, please refer to the [Messages Guide](docs/messages.md).

## Documentation

- [Configuration Guide](docs/configuration.md)
- [Messages Guide](docs/messages.md)

## License

This plugin is released under the [MIT License](LICENSE.md).

---

Feel free to contribute, report issues, and suggest enhancements on our [GitHub repository](https://github.com/yourusername/SupremeFriends). If you need assistance or have questions, please don't hesitate to reach out.

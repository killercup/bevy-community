# bevy-community
A listing of Bevy community members which is displayed on the Bevy website

## How To Add Yourself

Create a new file called `YOUR_GITHUB_USERNAME.toml` using one of the following links:
* [Bevy Community Member](https://github.com/bevyengine/bevy-community/new/main/Community%20Members): Anyone is allowed to create a community member entry.
* [Bevy Org Member](https://github.com/bevyengine/bevy-community/new/main/Org%20Members): Use this link only if you are a Bevy Org member.
* [Bevy Maintainer](https://github.com/bevyengine/bevy-community/new/main/Maintainers): Use this link only if you are a Bevy Maintainer.

Paste the template below into the file and fill out the fields that are relevant to you. Remove any optional fields that are not relevant to you.

## Entry Format

You can use the following fields in a toml file:

```toml
# Name you want to appear with. This can be whatever name/alias makes you most comfortable.
# Mandatory
name = "Me, Myself and I"

# File name of your profile picture if you uploaded one
# If you provide a file, be mindful of its size
# If you also add your github profile, you can use "GitHub" to use your GitHub profile picture
# This can be any image that follows our code of conduct.
# Optional
profile-picture = "GitHub"

# Short presentation of yourself. This has a limit of 180 characters.
# Optional
bio = ""

# Link to your sponsoring page, GitHub Sponsor, Patreon, Buy Me a Coffee, ...
# Optional
sponsor = ""

# Social links

# Will link to https://github.com/<username>
# Optional
github = "username"

discord = "DiscordUsername#1234"
# This allows direct linking to your profile for people with a shared server
# https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-
# Optional
discord-userid = ""

## Will link to https://<instance.com>/@<username>
# Optional
mastodon = "@username@instance.com"

## Will link to https://twitter.com/<username>
# Optional
twitter = "username"

## Will link to https://<username>.itch.io/
# Optional
itch-io = "username"

## Will link to http://store.steampowered.com/developer/<developer_name>
# Optional
steam-developer = "developer_name"

## Free link, will be displayed as is
# Optional
website = "https://mywebsite.com"
```

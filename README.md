# CarThingfy

## Not tested. I do not have Spotify Premium in my pockets.

A Spotify Car Thing interface clone for iOS 15.8.3+. This app mimics the interface of Spotify's Car Thing device, providing a car-friendly interface for controlling your Spotify playback.

## Requirements

- iOS 15.8.3 or later (why 15 you might ask, because I want to be backwards compatible t'ill iPhone 7
- iPhone (preferrably an older one, but not your main device.) or iPad (not recommended as the app is not optimized yet)
- Active Spotify Premium account
- Internet connection

## Setup Instructions

### 1. Create a Spotify Developer Account
   - Go to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/)
   - Create a new application
   - Add `carthingfy://` as a Redirect URI in your app settings
   - Note down your Client ID

### 2. Configure CarThingfy
   - Launch the app
   - Enter your Spotify Client ID and Client Secret when prompted
   - Sign in with your Spotify account (I do not get any of the credentials, as we just open Spotify's website.)
   - The app will store your Client ID and secret for future use

## Features

"Just like the real one"

- Car-friendly and Touch interface similar to Spotify Car Thing
- Now playing information display
- Search functionality
- Recently played tracks (currently I do not know if it works)
- Playlist support
- Landscape orientation support
- Dynamic background colors based on album artwork
- Touch-friendly controls optimized for car use

## Development

This app is built using:
- SwiftUI for the user interface
- Spotify Web API for music playback and control
- AuthenticationServices for OAuth2 authentication
- Minimum deployment target: iOS 15.8.3
- Plans: (in releases)

# README.md
# Home Network & Media Server Setup

## Overview
A self-hosted home server environment providing secure remote access, 
optimized network performance, and media streaming for personal and 
shared use.

## Goal
To build a reliable home server that my friends and I could securely connect to 
remotely, while improving overall home network performance and hosting 
a self-managed media library.

## What I Built
- **Remote Access:** Configured Tailscale VPN to allow secure remote 
  connections to my home network without exposing risky open ports to 
  the public internet.
- **Network Optimization:** Diagnosed slow WiFi performance and split 
  devices across 2.4GHz and 5GHz bands, cutting average ping from ~44ms 
  to ~21ms and noticeably improving throughput.
- **DNS Management:** Switched network-wide DNS to Cloudflare's family 
  filter for improved security and content filtering.
- **Media Server:** Deployed Jellyfin as a self-hosted media server, 
  configuring direct play and hardware transcoding for smooth playback 
  across devices.
- **Game Server:** Built and maintain a Paper Minecraft server (1.21.1) 
  with persistent world management, accessible remotely via Tailscale.

## Tools & Technologies
Tailscale, Cloudflare DNS, Jellyfin, Paper Minecraft Server, Windows 
networking configuration

## Challenges & What I Learned
Diagnosing the network slowdown required understanding how band 
congestion affects WiFi performance in a multi-device household. 
Configuring Tailscale taught me practical VPN concepts (mesh networking, 
node authentication) beyond textbook theory. Setting up Jellyfin's 
transcoding also required learning how codec compatibility affects 
playback performance across different client devices.

## Result
A stable, secure home network that supports remote access, faster 
everyday performance, and self-hosted media streaming — maintained 
and expanded over several months of ongoing work.

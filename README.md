# pixelflut-proxy

Proxy for the [pixelflut server](https://github.com/hf-21/pixelflut).

## Why?

It would be great to have a dedicated component to track, monitor, delay or even modify the traffic between the pixelflut-server and the -clients.


## Possible features

#### 💾 Recording

Record (drawing) traffic with timestamps to be able to playback specific sections or even the whole event on a live pixelflut canvas

#### 📊 Monitoring

Track the whole traffic to write (and visualize) metrics like

- Which IP created the most traffic in a specific period of time
- Which area of the canvas is the most used one
- What is the most popular used color
- Who has the most concurrent connections
- General traffic bandwith

#### ✏️ Modification

Tamper with the ongoing traffic, maybe even introduce mini games or temporary events like

- Invert given coordinates for a specific amount of time
- Drop every n-th request
- Shift whole canvas sections
- "Block" canvas areas
- Change colors randomly

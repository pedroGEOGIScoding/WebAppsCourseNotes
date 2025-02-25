# REACT

Class: FRONTEND

Notes: React Leaflet

Leaflet is the leading open-source JavaScript library for mobile-friendly interactive maps.

React Leaflet provides bindings between React and Leaflet. It does not replace Leaflet, but leverages it to abstract Leaflet layers as React components.

Quick start guide:

<aside>
ℹ️

[https://leafletjs.com/examples.html](https://leafletjs.com/examples.html)

</aside>

Example:

```jsx
const position = [51.505, -0.09]
        
render(
  <MapContainer center={position} zoom={13} scrollWheelZoom={false}>
    <TileLayer
      attribution='&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
      url="https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png"
    />
    <Marker position={position}>
      <Popup>
        A pretty CSS3 popup. <br /> Easily customizable.
      </Popup>
    </Marker>
  </MapContainer>
)
```
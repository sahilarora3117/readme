<div>
  <h1 align="center">CIPHER</h1>
  <h2 align="center">Encode and decode text</h2>
  <p align="center">A simple application for encoding and decoding text</p>
  <p align="center">Designed for <a href="https://elementary.io">elementary OS</p>
</div>
<p align="center">
  <a href="https://appcenter.elementary.io/com.github.arshubham.cipher.desktop">
    <img src="https://appcenter.elementary.io/badge.svg" alt="App Center">
  </a>
</p>
<p align="center">
<img src="https://github.com/arshubham/cipher/blob/master/data/images/Screenshot%20from%202018-01-14%2013.09.47.png" alt="screenshot">
<h1>Features</h1>
<br>
Cipher is a free and open souce encoding and decoding app specially designed for elementary os. The Cipher app can currently encode and decode between six different ciphers namely:<br><br>
1. Caesar Shift Cipher<br>
2. Atbash Cipher<br>
3. Polybius Square Cipher<br>
4. Rot13 Cipher<br>
5. Base64 Encoding<br>
6. ASCII Encoding<br>

<br>
</p>
<p align="center">
  <img src="https://github.com/arshubham/cipher/blob/master/data/images/icons/128/com.github.arshubham.cipher.svg" alt="preview"/>
</p>
<h1>Installation</h1>
<h2>Requiered Dependencies</h2><br>
1. granite<br>
2. gobject-2.0<br>
3. gtk+-3.0<br>
4. glib-2.0<br>
5. gee-0.8<br>
6. libgda-5.0<br>
<h2>Installation</h2>
To install this app in firstly clone this repository and type the follwing commands in your terminal 

```
sudo apt install elementary-sdk
sudo apt install meson
```

Now cd to Cipher
```
mkdir build
```
Now cd to build 
```
meson ..
ninja
sudo ninja install
```

<h1>Contribute</h1>
We welcome user contributions. Any type of help would be fine.

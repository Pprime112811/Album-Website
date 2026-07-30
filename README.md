<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Team Prime | Official Website</title>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  background: #07070b;
  color: white;
}

/* NAVIGATION */

nav {
  position: fixed;
  top: 0;
  width: 100%;
  padding: 18px 7%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: rgba(7,7,11,.85);
  backdrop-filter: blur(15px);
  z-index: 1000;
  border-bottom: 1px solid rgba(255,255,255,.08);
}

.logo {
  font-size: 24px;
  font-weight: 900;
  letter-spacing: 3px;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 24px;
  font-weight: bold;
}

nav a:hover {
  opacity: .6;
}

/* HERO */

.hero {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 120px 20px 60px;

  background:
    radial-gradient(circle at 50% 20%, #493b91, transparent 40%),
    radial-gradient(circle at 20% 80%, #233c80, transparent 35%),
    linear-gradient(135deg,#08080c,#151522);
}

.hero h1 {
  font-size: clamp(60px,12vw,150px);
  font-weight: 900;
  letter-spacing: -7px;
}

.hero p {
  color: #c7c7d1;
  font-size: 20px;
  margin-top: 15px;
}

.button {
  display: inline-block;
  margin-top: 30px;
  padding: 15px 30px;
  border-radius: 999px;
  background: white;
  color: black;
  text-decoration: none;
  font-weight: bold;
  transition: .2s;
}

.button:hover {
  transform: scale(1.06);
}

/* SECTIONS */

section {
  max-width: 1200px;
  margin: auto;
  padding: 110px 7%;
}

.section-title {
  font-size: 48px;
  margin-bottom: 45px;
}

/* ALBUM */

.album {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 55px;
  align-items: start;
}

.album-cover {
  aspect-ratio: 1;
  border-radius: 25px;

  background:
    linear-gradient(135deg,#536dfe,#9c27b0,#ff4081);

  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;

  box-shadow: 0 30px 90px rgba(0,0,0,.55);
}

.album-cover h3 {
  font-size: clamp(45px,6vw,75px);
  font-weight: 900;
  letter-spacing: -3px;
}

.album-info p {
  color: #aaaab6;
  line-height: 1.7;
  margin-bottom: 30px;
}

/* TRACKS */

.track {
  margin-bottom: 28px;
}

.track-title {
  font-size: 20px;
  font-weight: bold;
  margin-bottom: 10px;
}

.track-number {
  color: #888895;
  margin-right: 8px;
}

iframe {
  width: 100%;
  height: 170px;
  border: 0;

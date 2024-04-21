<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rumah 3D</title>
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
</head>
<body>
    <a-scene background="color: #333333">
        <!-- Kamera -->
        <a-entity camera position="0 5 15" look-controls></a-entity>
        
        <!-- Cahaya -->
        <a-light type="ambient" color="#888"></a-light>
        <a-light type="directional" intensity="0.5" position="2 4 3"></a-light>
        
        <!-- Dinding belakang -->
        <a-box position="0 2.5 -5" width="10" height="5" depth="0.2" color="#666666" shadow>
            <a-text value="Dinding Belakang" color="black" align="center" position="0 0 0.2" scale="1.5 1.5 1.5"></a-text>
        </a-box>
        
        <!-- Dinding kiri -->
        <a-box position="-5 2.5 0" width="0.2" height="5" depth="10" color="#666666" shadow>
            <a-text value="Dinding Kiri" color="black" align="center" position="0 0 0.2" scale="1.5 1.5 1.5" rotation="0 90 0"></a-text>
        </a-box>
        
        <!-- Dinding kanan -->
        <a-box position="5 2.5 0" width="0.2" height="5" depth="10" color="#666666" shadow>
            <a-text value="Dinding Kanan" color="black" align="center" position="0 0 0.2" scale="1.5 1.5 1.5" rotation="0 90 0"></a-text>
        </a-box>
        
        <!-- Dinding depan -->
        <a-box position="0 2.5 5" width="10" height="5" depth="0.2" color="#666666" shadow>
            <a-text value="Dinding Depan" color="black" align="center" position="0 0 0.2" scale="1.5 1.5 1.5"></a-text>
        </a-box>
        
        <!-- Atap -->
        <a-entity position="0 7 -1" shadow>
            <a-cone radius-bottom="10" radius-top="0" height="5" color="#999999">
                <a-text value="Atap" color="black" align="center" position="0 2.5 0" scale="1.5 1.5 1.5"></a-text>
            </a-cone>
        </a-entity>
        
        <!-- Pintu -->
        <a-box position="0 1.25 5.1" width="2" height="2.5" depth="0.1" color="#999999" shadow>
            <a-text value="Pintu" color="black" align="center" position="0 0 0.2" scale="1.5 1.5 1.5"></a-text>
            <a-entity position="0 4 4.5">
                <a-text value="Raifan Ahmad Kurniawan" color="black" align="center" scale="1 1 1"></a-text>
                <a-text value="NPM: 2113025018" color="black" align="center" position="0 -0.3 0" scale="1 1 1"></a-text>
              <a-text value="Atap" color="black" align="center" position="0 0.7 0" scale="1 1 1"></a-text>
            </a-entity>
        </a-box>
        
        <!-- Jendela kiri -->
        <a-box position="-3.5 3 5.1" width="1" height="1" depth="0.1" color="#999999" shadow>
            <a-text value="Jendela Kiri" color="black" align="center" position="0 0 0.2" scale="1.5 1.5 1.5"></a-text>
        </a-box>
        
        <!-- Jendela kanan -->
        <a-box position="3.5 3 5.1" width="1" height="1" depth="0.1" color="#999999" shadow>
            <a-text value="Jendela Kanan" color="black" align="center" position="0 0 0.2" scale="1.5 1.5 1.5"></a-text>
        </a-box>
    </a-scene>
</body>
</html>

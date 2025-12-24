* {
    box-sizing: border-box;
}

body {
    margin: 0;
    padding: 0;
    font-family: 'Roboto', sans-serif;
    color: #ffd700;
    background: linear-gradient(rgba(0,0,0,0.65), rgba(0,0,0,0.65)),
                url('https://i.imgur.com/9bZ2K7m.jpg') no-repeat center/cover fixed;
    min-height: 100vh;
    text-align: center;
}

.container {
    max-width: 420px;
    margin: 0 auto;
    padding: 15px;
}

h1 {
    font-family: 'Cinzel', serif;
    font-size: 28px;
    margin: 10px 0 20px;
    text-shadow: 0 0 15px #000;
}

#playerInfo {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
    margin-bottom: 15px;
    font-size: 18px;
}

#playerAvatar {
    width: 56px;
    height: 56px;
    border-radius: 50%;
    border: 3px solid #ffd700;
    object-fit: cover;
}

#stats {
    background: rgba(0,0,0,0.7);
    padding: 15px;
    border-radius: 15px;
    border: 2px solid #ffd700;
    margin: 15px 0;
}

.stat {
    font-size: 18px;
    margin: 10px 0;
}

#quest {
    background: rgba(0,50,0,0.6);
    padding: 12px;
    border-radius: 12px;
    margin: 15px 0;
    border: 1px solid #00ff88;
    font-size: 16px;
}

#monsterContainer {
    position: relative;
    margin: 25px 0;
}

#monster {
    width: 180px;
    cursor: pointer;
    transition: transform 0.1s;
    filter: drop-shadow(0 0 15px #000);
}

#monster:active {
    transform: scale(0.92);
}

.progress-bar {
    background: #333;
    border-radius: 10px;
    height: 22px;
    margin: 10px auto;
    width: 80%;
    overflow: hidden;
    border: 2px solid #ffd700;
}

.progress-fill {
    height: 100%;
    background: linear-gradient(90deg, #ff4444, #ffaa00);
    width: 100%;
    transition: width 0.3s ease;
}

.monster-hp {
    font-size: 18px;
    margin-top: 5px;
}

.hit-effect {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 42px;
    font-weight: bold;
    color: #ff3333;
    pointer-events: none;
    animation: hit 0.8s ease-out forwards;
    text-shadow: 3px 3px 6px #000;
}

@keyframes hit {
    0% { opacity: 1; transform: translate(-50%, -50%) scale(0.5); }
    100% { opacity: 0; transform: translate(-50%, -120px) scale(1.5); }
}

.shop {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    justify-content: center;
    margin: 25px 0;
}

button {
    background: linear-gradient(#8b6914, #b8860b);
    color: white;
    border: 2px solid #ffd700;
    border-radius: 12px;
    padding: 14px 18px;
    font-size: 16px;
    cursor: pointer;
    box-shadow: 0 5px 10px rgba(0,0,0,0.6);
    transition: all 0.2s;
    min-width: 140px;
}

button:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 15px rgba(0,0,0,0.7);
}

button:disabled {
    opacity: 0.5;
    cursor: not-allowed;
    transform: none;
}

.share-btn {
    background: linear-gradient(#006400, #008000);
}

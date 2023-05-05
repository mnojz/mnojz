<html>
<body>
<div class="wrapper">
    <div class="typing-demo">
      Hi, I am Manoj Joshi
    </div>
</div>
<style>
.wrapper {
  height: 100vh;
  display: grid;
  place-items: center;
}

.typing-demo {
  width: 22ch;
  animation: typing 6s steps(22) infinite, blink 1s step-end infinite;
  white-space: nowrap;
  overflow: hidden;
  border-right: 3px solid;
  font-family: monospace;
  font-size: 2em;
  color:blue;
}

@keyframes typing {
  0%,90%,100% {width: 0}
  20%{width:22ch}  
  80%{width:22ch}
}
    
@keyframes blink {
  50% {
    border-color: transparent
  }
}
</style>    
</body>
</html>

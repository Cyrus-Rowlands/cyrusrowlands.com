@keyframes typewriter {
  0% {
    width: 0;
  }

  100% {
    width: 24ch;
  }
}

.typewriter {
  white-space: nowrap;
  overflow: hidden;
  font-family: monospace;
  margin-left: auto;
  margin-right: auto;
  animation: typewriter 2.4s steps(24) 0s alternate infinite;
}

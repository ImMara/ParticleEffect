---
## Install & Run

```
npm install
```

After installing all depencies, you can run the server with
```
npm run start
```
that will open a new window on your browser http://localhost:8080/

---

### 📝 Vertex Shader Sample
``` 
void main() {
  vec4 mvPosition = modelViewMatrix * vec4( position, 1.0 );
  gl_Position = projectionMatrix * mvPosition;
  gl_PointSize = 8.0 / -mvPosition.z;
}
```

### 📝 Fragment Shader Sample
``` 
void main() {
 gl_FragColor = vec4(1.0, 1.0, 1.0, 1.0);
}
```


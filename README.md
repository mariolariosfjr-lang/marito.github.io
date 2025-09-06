# marito.github.io
Marito code programming language
# Code
``` lua
/myVariable = "Hello World";

func sayHello() {
    cg(myVariable);
}

w (true) {
    remember (myVariable == "Hello World") range {
        cg("Loop running...");
        break;
    }
}

sayHello();
```
# three.js will be
``` javascript
// Set up scene, camera, and renderer
        const scene = new THREE.Scene();
        const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
        const renderer = new THREE.WebGLRenderer();
        renderer.setSize(window.innerWidth, window.innerHeight);
        document.body.appendChild(renderer.domElement);

        // Add a cube
        const geometry = new THREE.BoxGeometry(1, 1, 1);
        const material = new THREE.MeshBasicMaterial({ color: 0x00ff00 });
        const cube = new THREE.Mesh(geometry, material);
        scene.add(cube);

        camera.position.z = 5;

        // Animation loop
        function animate() {
            requestAnimationFrame(animate);

            cube.rotation.x += 0.01;
            cube.rotation.y += 0.01;

            renderer.render(scene, camera);
        }
        animate();
```
# translated to
``` marito
        /scene = new THREE.Scene();
        /camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
        /renderer = new THREE.WebGLRenderer();
        renderer.setSize(window.innerWidth, window.innerHeight);
        document.body.appendChild(renderer.domElement);

        // Add a cube
        /geometry = new THREE.BoxGeometry(1, 1, 1);
        /material = new THREE.MeshBasicMaterial({ color: 0x00ff00 });
        /cube = new THREE.Mesh(geometry, material);
        scene.add(cube);

        camera.position.z = 5;

        // Animation loop
        func animate() {
            requestAnimationFrame(animate);

            cube.rotation.x += 0.01;
            cube.rotation.y += 0.01;

            renderer.render(scene, camera);
        }
        animate();
```
# How to Use it
``` css
Use this three.js code to copy and paste

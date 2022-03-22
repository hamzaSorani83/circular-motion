# circular-motion
  (canvas js)

# live demo: https://hamzasorani83.github.io/circular-motion/

# initial position in middle:
  - const mouse = {
    x: innerWidth / 2,
    y: innerHeight / 2,
  }

# change position on mousemove: 
  - addEventListener('mousemove', (event) => {
    mouse.x = event.clientX;
    mouse.y = event.clientY;
  })


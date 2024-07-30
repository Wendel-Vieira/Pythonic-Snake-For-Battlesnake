<!-- logo -->
<br />
<div align="center">
  <a href="https://github.com/Wendel-Vieira/Pythonic-Snake-For-Battlesnake">
    <img src="https://res.cloudinary.com/micronetonline/image/upload/c_crop,h_1081,w_1389,x_0,y_0/v1623965831/tenants/d67d1859-c8c5-41c2-91ff-23438f7f2e89/4ecbc74ac2704ae591a88e522461ff79/Full-Logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Battlesnake AI</h3>

  <p align="center">
    A competitive Battlesnake AI that got top 60 worldwide.
    <br />
    <a href="https://docs.battlesnake.com">View Documentation</a>
    ·
    <a href="https://github.com/Wendel-Vieira/Pythonic-Snake-For-Battlesnake/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/Wendel-Vieira/Pythonic-Snake-For-Battlesnake/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#key-features">Key Features</a></li>
        <li><a href="#console-board-representation">Console Board Representation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- about section -->
## About The Project

<a href="https://docs.battlesnake.com">
  <img src="https://github.com/user-attachments/assets/a0f64758-c22a-4727-a6d7-2b4f48e584ac" alt="Project Image" width="600" height="300">
</a>


### Key Features
- **A Star Pathfinding Algorithm**
- **Flood Fill Algorithm**
- **Collision Detection**
- **Console Board Representation**

### Console Board Representation

This representation of the game on the console was very important to implement because it uses information obtained from the flood fill algorithm, and with that we are able to debug and check if anything is going wrong with it.  
  
Each snake has its own colors, with the player snake always being blue by default. The '@' represents the body of a snake, and the '3' its head.  
Each free tile is represented as a dot, and its color is determined by the snake that can get to that tile first. White dots are tiles where no snake can get to them first, so no snake "has" it. 'F' represents food available on the board, and its color is also dependent on which snake can get to it before other snakes.

[![Console Board][console-board]](https://docs.battlesnake.com)

<!-- ROADMAP -->  
## Roadmap

- [x] Implement Collision Detection
- [x] Implement Flood Fill Algorithm
- [x] Implement A Star Pathfinding Algorithm
- [x] Implement Console Board Representation
- [ ] Implement Minimax Algo with Alpha Beta Pruning
- [ ] Optimize Flood Fill and Pathfinding

<!-- CONTRIBUTING -->
## Contributing

Contributions are welcome! Follow these steps:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/Feature`)
3. Commit your changes (`git commit -m 'Add some Feature'`)
4. Push to the branch (`git push origin feature/Feature`)
5. Open a pull request

<!-- LICENSE -->
## License

Distributed under the MIT License.

<!-- CONTACT -->
## Contact

- email: fvwendel@gmail.com
- github: [github.com/Wendel-Vieira](https://github.com/Wendel-Vieira)

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

- [Battlesnake](https://battlesnake.com) for providing this amazing competitive game 😊.
- [Battlesnake Doc](https://docs.battlesnake.com) for their documentation on how to code your snake!

<!-- links and images -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[project-image]: https://github.com/user-attachments/assets/a0f64758-c22a-4727-a6d7-2b4f48e584ac
[console-board]: https://github.com/user-attachments/assets/131bc56e-0ff1-40d0-a1fe-8dc4ef8ca703

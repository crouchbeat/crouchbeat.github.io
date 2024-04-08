# Crouch Beat

Crouch Beat is an interactive web-based game designed to encourage physical activity through gameplay. Players control the game by crouching in front of their computer's webcam, which makes the on-screen character jump. The game combines fitness with fun, making it a unique addition to your daily workout routine or just a casual play.

## Features

- **Webcam Interaction**: Utilizes the webcam to detect player movements, specifically crouching, to control the game character.
- **Audio Feedback**: Includes various sound effects to enhance the gaming experience.
- **Score Tracking**: Keeps track of the player's score, which increases with successful jumps.
- **Social Sharing**: Allows players to share their scores on social media platforms like Twitter, Facebook, and WeChat.
- **Responsive Design**: The game is designed to be responsive, making it playable on various devices and screen sizes.

## How to Play

1. **Start the Game**: Open the game in your web browser. Make sure your webcam is enabled and positioned correctly.
2. **Crouch to Jump**: The game character jumps every time you move your face from top half of camera view to bottom half. The objective is to avoid obstacles and collect items to increase your score.
3. **Pause/Resume**: Press the `Esc` key to pause or resume the game.
4. **Share Your Score**: After the game ends, you can share your score on Twitter, Facebook, or WeChat to challenge your friends.

## Setup

To run Crouch Beat on your local machine, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/oatmeal3000/crouch-beat.git
   ```
2. Open the `index.html` file in a web browser with webcam access.

## Technologies Used

- HTML5 & CSS3 for layout and design.
- JavaScript for game logic and webcam interaction.
- TensorFlow.js and PoseNet for real-time pose estimation.
- jQuery for DOM manipulation (optional).

## Contributing

Contributions to Crouch Beat are welcome! Whether it's bug fixes, new features, or improvements to the documentation, feel free to fork the repository and submit a pull request.

## License

Crouch Beat is released under the MIT License. See the LICENSE file for more details.

## Acknowledgments

- TensorFlow.js and PoseNet for enabling real-time pose estimation.
- Sound effects and music obtained from [Free Sound](https://freesound.org/).

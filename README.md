# idea2img-optimizer

idea2img-optimizer is an experimental tool designed to bridge the gap between abstract mental imagery and concrete visual representations.  
It leverages AI-powered image generation and human-in-the-loop black-box optimization techniques to transform users' conceptual ideas into tangible visual content.

## Key Features

- Integration with Diffusers (image generation library) and Optuna (black-box optimization library)
- Human-in-the-loop feedback mechanism within a black-box optimization workflow for prompt refinement
- User-friendly interface for idea input and image evaluation

## How It Works

1. **Idea Input**: Users provide a set of keyword prompts (image tags) for image generation.
2. **Initial Generation**: The system generates a set of initial images based on randomly selected keywords from the user input.
3. **Human Feedback**: Users provide scores on the generated images, indicating how closely they align with their mental concept.
4. **Optimization**: The system utilizes this feedback to optimize the prompts and generate new images.
5. **Iteration**: Steps 3 and 4 are repeated until the user is satisfied with the result.

## Getting Started

WIP

## License

This project is licensed under the [MIT License](LICENSE).

---

If you have any questions or feedback, please open an issue in this repository.
# uv-modal-example

This is an example project that demonstrates how to use Modal to run a function locally and remotely.

## Project Structure

The project consists of a single file, `main.py`, which defines a Modal app and a function `f` that takes an integer `i` as input.

## Functionality

The function `f` checks if the input `i` is even or odd and prints a message accordingly. It then returns the square of the input.

The `main` function runs the `f` function locally, remotely on Modal, and in parallel and remotely on Modal.

## Running the Project

To run the project, you can use the following commands:

- `python main.py` to run the project locally
- `modal run main.py` to run the project remotely on Modal

## Dependencies

The project depends on the following libraries:

- `modal` for running the function remotely on Modal
- `fastapi` and `uvicorn` for serving the function as a web API

## License

This project is licensed under the MIT License.

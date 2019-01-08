# Machine Learning Experiments

A collection of quick-and-dirty machine learning-related experiments, primarily created for the purpose of exploring various aspects of machine learning and AI.

- **GeoLearnV3.ipynb**: An attempt to use a convolutional neural network to distinguish between geometric shapes and localize them precisely in an image (similar to semantic segmentation). The motivation for this is to select a neural network architecture that would be able to simultaneously classify and localize specific features. Originally, it was created in response to some difficulties encountered in a more difficult experiment (i.e. localizing a user's finger within a camera image)

- **Dotter.ipynb**: A simple testbed for reinforcement learning algorithms in the form of a cat-and-mouse game where the agent is controlled by a mouse character, which is chased by simple cat characters (programmed deterministically to move in the mouse's direction) and can collect cheese to obtain points. The game continues indefinitely, but a penalty is given every time the mouse is "eaten" by a cat. The example includes a Proximal Policy Gradient agent and a Deep Q Learning agent with implementations provided by Tensorforce.

- **cozmo**: Experiments with the Cozmo robot. Currently, it contains one experiment in which Cozmo is controlled by an LSTM RNN, attempting to replicate human control by looking at the sequence of readings and previously performed actions (initially trained with human control) and attempting to replicate the following actions in the dataset.

## Bhaptics Unity Demo

This Unity project demonstrates some basic functionality of the Bhaptics haptic technology, including body hit, fast heartbeat, and custom haptic feedback on the Bhaptics vest. The project is written in C# and uses the Bhaptics SDK to interact with the haptic vest.

## Getting Started

To run the demo, you'll need to have a Bhaptics vest and the Bhaptics Unity plugin installed on your computer. You can download the plugin from the [Bhaptics developer portal](https://developers.bhaptics.com/unity-plugin/) and follow the installation instructions.

Once you have the plugin installed, you can open the project in Unity and navigate to the `bHapticsDemoScene` scene. In this scene, you'll find three buttons that trigger different types of haptic feedback on the vest:

- **Body Hit**: This button triggers a short burst of haptic feedback that simulates a body hit.
- **Fast Heartbeat**: This button triggers a looping haptic feedback that simulates a fast heartbeat.
- **Custom Haptic**: This button triggers a custom haptic feedback that writes the letter "W" on the front and rear of the vest.

You can also view the `bHapticsCommands.cs` script to see how the haptic feedback is triggered using the Bhaptics SDK.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Thanks to Bhaptics for providing the haptic technology and SDK used in this demo.
- Thanks to the Unity community for creating helpful resources on using the Bhaptics SDK in Unity.

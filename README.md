# Unity-ARFoundation-echo3D-demo-Face-Change
Simple face change demo with Unity, AR Foundation, and echo3D

## Register
Don't have an API key? Make sure to register for FREE at [echo3D](https://console.echo3D.co/#/auth/register).

## Setup
* Create a new Unity project.
* Clone the [Unity-ARFoundation-echo3D](https://github.com/echo3Dco/Unity-ARFoundation-echo3D) sample code.
* Open the sample scence under `AR Foundation\Scenes\FaceTracking\FaceMesh.unity`.
* [Set the API key](https://docs.echo3D.co/unity/using-the-sdk) in the `echo3D.cs` script inside the `echo3D\echo3D.prefab` using the the Inspector.
* [Add an image hologram](https://docs.echo3D.co/web-console/manage-pages/content-page/how-to-add-content) by uploding one of the _face-#.jpg_ files from the [assets](./assets/) folder to the console.
* Overwrite the existing _echo3D/CustomBehaviour.cs_ script with the new [_CustomBehaviour.cs_](./CustomBehaviour.cs) file.

## Build & Run
* [Build and run the AR application](https://docs.echo3D.co/unity/adding-ar-capabilities#4-build-and-run-the-ar-application). Verify that the `AR Foundation\Scenes\FaceTracking\FaceMesh` scene is ticked in the `Scenes in Build` list and click `Build And Run`.

## Learn more
Refer to our [documentation](https://docs.echo3D.co/unity/) to learn more about how to use Unity and echo3D.

## Support
Feel free to reach out at [support@echo3D.co](mailto:support@echo3D.co) or join our [support channel on Slack](https://go.echo3D.co/join). 

## Screenshots
![Phone screenshot](/images/Phone.gif)
![echo3D console screenshot](/images/Console.png)

# Unity-ARFoundation-echoAR-demo-Face-Change
Simple face change demo with Unity, AR Foundation, and echoAR

## Register
Don't have an API key? Make sure to register for FREE at [echoAR](https://console.echoar.xyz/#/auth/register).

## Setup
* Create a new Unity project.
* Clone the [Unity-ARFoundation-echoAR](https://github.com/echoARxyz/Unity-ARFoundation-echoAR) sample code.
* Open the sample scence under `AR Foundation\Scenes\FaceTracking\FaceMesh.unity`.
* [Set the API key](https://docs.echoar.xyz/unity/using-the-sdk) in the `echoAR.cs` script inside the `echoAR\echoAR.prefab` using the the Inspector.
* [Add an image hologram](https://docs.echoar.xyz/web-console/manage-pages/content-page/how-to-add-content) by uploding one of the face-#.jpg file from the [assets](./assets/) folder to the console.
* Overwrite the exisitng _echoAR/CustomBehaviour.cs_ script with the new [_CustomBehaviour.cs_](./CustomBehaviour.cs) file.

## Build & Run
* [Build and run the AR application](https://docs.echoar.xyz/unity/adding-ar-capabilities#4-build-and-run-the-ar-application). Verify that the `AR Foundation\Scenes\FaceTracking\FaceMesh` scene is ticked in the `Scenes in Build` list and click `Build And Run`.

## Learn more
Refer to our [documentation](https://docs.echoar.xyz/unity/) to learn more about how to use Unity and echoAR.

## Support
Feel free to reach out at [support@echoAR.xyz](mailto:support@echoAR.xyz) or join our [support channel on Slack](https://join.slack.com/t/echoar/shared_invite/enQtNTg4NjI5NjM3OTc1LWU1M2M2MTNlNTM3NGY1YTUxYmY3ZDNjNTc3YjA5M2QyNGZiOTgzMjVmZWZmZmFjNGJjYTcxZjhhNzk3YjNhNjE). 

## Screenshots
![Phone screenshot](/images/Phone.gif)
![echoAR console screenshot](/images/Console.png)
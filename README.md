# Ragnarok
Ragnarok is a doom for people trying to steal someone's assets by downloading from illegal sites or requesting on Discord servers. If you ever find such a person, please send them **thirdpersoncontroller.packagemanager**.

**"thirdpersoncontroller.packagemanager"** contains a script called **"ThirdPersonController.cs"** which, when imported, automatically does the following:
1. Gets the name of the computer user profile,
2. Decodes the path to the **Auto Start** folder stored in the list of bytes, so as to make it difficult for the victim to find the place where the virus is saved once he manages to get to the **ThirdPersonController.cs** script,
3. Creates a **_.bat** file in the path from step **2.**,
4. The **_.bat** file code immediately shuts down the computer,
5. Changes the **_.bat** file attributes to be hidden,
6. Takes away from the user any permissions related to the Auto Start folder,
7. Opens the **_.bat** file which ends with the immediate shutdown of the computer,
8. Every time the victim tries to turn on the computer, the **_.bat** file will be called and the computer will shut down again. 
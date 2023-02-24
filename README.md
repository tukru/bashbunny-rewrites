# bashbunny-rewrites
fix'n shit on the sneaky
This Bash Bunny payload automatically checks for any upgrades to Hak5 libraries on the Hak5 Github repository, upgrades any applicable libraries, and then clears the loot folder and cleans up the file system.
Requirements

    Hak5 Bash Bunny
    An internet connection
    Github account with SSH key added to your device

How to Use

    Copy the library-updater.txt file to the root directory of the Bash Bunny.
    Plug the Bash Bunny into the target computer.
    The Bash Bunny will automatically execute the payload.
    If any Hak5 library upgrades are available, the payload will automatically upgrade them.
    Once completed, the Bash Bunny will clear the loot folder and clean up the file system.
    Unplug the Bash Bunny from the target computer.

Configuration

You need to add your Github SSH key to your device to avoid authentication prompt.
You can get started by visiting https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account
Payload Steps

    Set the LED to blue to indicate the start of the payload.
    Create the loot directory and clean up any previous files.
    Set up the Bash Bunny to use HID storage mode.
    Get the latest library upgrade information from the Hak5 Github repository.
    Check if any library upgrades are available.
    Upgrade any applicable libraries.
    Clean up the loot directory and file system.
    Set the LED to green to indicate the end of the payload.

LED Status

    Blue: The payload is starting.
    Yellow: The Bash Bunny is running the payload and checking for library upgrades.
    White: The Bash Bunny is cleaning up the loot folder and file system.
    Green: The payload is completed.

Security Considerations

This payload requires an internet connection and SSH key for Github. It is recommended to use this payload on a secure network and device. It is also recommended to review the payload code before using it to ensure it aligns with your ethical and legal considerations.
Credits

This payload was created by [Your Name]. The code was developed using the Hak5 Bash Bunny documentation and sample payloads, and with inspiration from the Hak5 community.

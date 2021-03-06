# Hotbar Menu Template

This Macro gives you a collapsable Hotbar Menu. It can be edited to have multiple hotbars if preferred. 

See the [Class Menu](https://github.com/Discord-Coding-Community/FFXIV-Macros/tree/master/Miscellaneous/Class%20Menu) Macro for an example of one with multiple Hotbars.

## Usage

 - Simply replace `[CLASS INITIALS]` with the initials for the class of which you are copying the shared hotbar from.
    - Example:
    ```cs
        /hotbar copy BRD 10 share 10
    ```
 - For each new hotbar added make sure replace `[HOTBAR NUMBER]` with the hotbar number.
 - Next, add all of you items to both the shared and unshared versions of the hotbar(s) specified in the Macro, then share, unshare, and re share the hotbar(s) specified in the Macro.
 - Once done hide the hotbar(s) specified in the Hotbar Macro and add the Hotbar Macro to a visible shared hotbar.

## Notes

 - This Macro set can be finicky when setting up, so sometimes unsharing and re sharing the hotbar(s) specified in the Hotbar Macro before attempting to click it may be needed for it to save.
 - Make sure the shared and un shared version(s) of the hotbar(s) specified in the Hotbar Menu Macro are completely identical to each other.
 - Make sure you are making these on the same class that the Hotbar Menu Macro copies the items from for it to save.
 - Brackets `[]` refer to text to replace. **DO NOT** include the brackets `[]` in the `README.md` file, just replace the necessary fields as instructed.
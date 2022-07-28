# Photo Organizer

This script helps you organize your photos by moving them into designated folders based on their type.

## How to Use

1. **Save the script:** Save the script as `photos-organize` in a location on your system.

2. **Make it executable:** Open a terminal and run `chmod +x photos-organize`.

3. **Run the script:** Execute the script with the following command:

   ```bash
   ./photos-organize <source_directory> <target_directory>
   ```

   * `<source_directory>`: The directory containing the photos you want to organize.
   * `<target_directory>`: The directory where you want the organized photos to be moved.

**Example:**

```bash
./photos-organize /home/user/Pictures /home/user/Photos
```

This will organize photos from `/home/user/Pictures` into `/home/user/Photos`.

## Features

* **Live Photo Handling:** Moves Live Photos (`.heic` and `.mov`) to a separate "Live Photos" folder within the target directory.
* **Photo and Video Organization:** Distinguishes between photos (`.jpg`, `.jpeg`) and videos (`.mp4`, `.mov`) and places them accordingly.
* **File Date Synchronization:** Syncs the modified date of Live Photo files.

## Options

* **`-h` or `--help`:** Displays this help message.

## Notes

* The script assumes that your photos are in a standard directory structure.
* The script does not delete any files. It only moves them to the target directory.
* You can customize the script further by modifying the target directory names and file extensions.

## License

This tool is licensed under the [MIT License](LICENSE).

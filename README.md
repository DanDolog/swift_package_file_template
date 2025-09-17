# Swift Package File Template

## Problem
When creating a new Swift file inside a Swift Package, Xcode skips the filename prompt and generates an empty file without a header. This breaks consistency across projects and slows down development.

## Solution
This custom file template restores the filename dialog and adds a standard header comment to new Swift files inside Swift Packages.

## Installation
1. Copy the `Swift Package File.xctemplate` folder to: `[path_to_Xcode]/Contents/Developer/Library/Xcode/Templates/File Templates/MultiPlatform/Source`.
2. Restart Xcode.

## Usage
1. Try to create new File.
2. Choose `Swift Package File`.
3. Enter the desired filename and location inside your Swift Package.
4. A new Swift file will be created with the standard header.

## Enjoy
Happy coding! 🚀

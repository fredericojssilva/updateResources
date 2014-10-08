UpdateResources
===============

A bash script for sync the project resource folder with folder of the designer.

if the designer does something wrong. and he'll do :), you can revert the operation.

Setup
===============

Edit update_resources with your paths for: project resource folder, design resource folder and backup folder.

Usage
===============

chmod +x update_resources and then run it manually(./update_resources) or make an alias.

**./update_resources** executing without args will make a backup of your project folder and copy the contents of the designer for the project folder.

**./update_resources -revert** the arg -revert will restore your project resources with the backup.

**./update_resources -diff** show differences between your folder and designer folder

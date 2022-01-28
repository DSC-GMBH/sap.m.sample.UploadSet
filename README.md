## Reproducing the issue:

### Prepare
1. Download the repository
2. Run `npm i` and `npm run start` afterwards
3. Open the URL shown in console e.g. `http://localhost:8080`

### Default case

1. Add three or more testFiles by drag-and-drop or the browse icon
2. Watch the console output

[Browse](gifs/Browse.gif)

[DragAndDrop](gifs/DragAndDrop.gif)


### instantUpload set to false

1. Set property `instantUpload` to false in `Page.view.xml`
2. Add three or more testFiles by drag-and-drop or the browse icon
3. Try to delete the lowest added file


[InstantUploadFalse](gifs/InstantUploadFalse.gif)

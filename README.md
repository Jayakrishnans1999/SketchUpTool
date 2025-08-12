I’ve often seen talented 3D artists losing precious hours fixing inverted normals — a small but frustrating issue that can derail project timelines. Whether you’re preparing assets for real-time rendering or baked workflows, these fixes shouldn’t be a bottleneck.
So, I built Normal Flipper Tool for SketchUp 🛠️:
 ✅ Smart Detection – Only flips the faces that are actually inverted
 ✅ Works with complex meshes, groups, and components
 ✅ Quick UI for one-click fixes
 ✅ Safe and undo-friendly
These tools are designed not just for my team but for any artist struggling to meet deadlines while maintaining top-quality models.
💡 My goal is simple: eliminate repetitive technical hurdles so artists can focus on creativity.




INSTALLATION INSTRUCTIONS FOR SKETCHUP PRO V25.0.660:

METHOD 1 - Via Extension Manager (Recommended):
1. Save this code as 'normal_flipper.rb'
2. Open SketchUp
3. Go to Window > Extension Manager
4. Click 'Install Extension'
5. Select the .rb file
6. Restart SketchUp

METHOD 2 - Manual Installation:
1. Save this code as 'normal_flipper.rb'
2. Copy the file to your SketchUp Plugins folder:
   Windows: C:\Users\[username]\AppData\Roaming\SketchUp\SketchUp 2025\SketchUp\Plugins\
   Mac: ~/Library/Application Support/SketchUp 2025/SketchUp/Plugins/
3. Restart SketchUp

USAGE:
1. Select faces, groups, or components in your model
2. Access via Plugins > Normal Flipper menu
3. Choose "Fix Only Inverted Faces (Smart)" for intelligent correction
4. Use "Face Orientation Help" for visualization tips

FEATURES:
- Smart detection of inverted faces only
- Works with individual faces, groups, and components  
- Batch processing of multiple objects
- Undo support
- Safe operation with error handling
- Both smart fix and flip-all options

FACE ORIENTATION VISUALIZATION:
- View > Face Style > Monochrome (white = front, gray = back)
- View > Edge Style > Back Edges (shows back-facing edges differently)

The tool will appear in both the Plugins menu and as a toolbar for easy access.

Copy the "normal_flipper.rb" file and paste it in the "C:\Program Files\SketchUp\SketchUp 2025\SketchUp\ShippedExtensions".
Run sketchUp and in Extension manager -Enable the normal_flipper plugin. Don't forget to give access/trusted when asked.

Thanks. Enjoy, stay creative....



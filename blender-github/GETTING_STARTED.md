# Blender studies & Little Cabin

Editable Blender projects shared by **Aikun Wang** for learning, exploration, and reuse.

Portfolio: https://aikunwang.com/projects.html#work
License: original contributions under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/); see LICENSE.md and THIRD_PARTY_ASSETS.md.

## Start here

1. Download and fully extract the ZIP, preserving the folder structure.
2. Open **Little cabin WATER2.blend** in Blender **4.1**. This is the most recently saved cabin variant in the supplied collection and has 102 objects.
3. Explore the Outliner, materials, lights, camera, and fluid modifiers. Other cabin variants show earlier scene states.
4. Keep the texture and cache folders beside the .blend files. Paths in these distribution copies have been repaired to be relative.

## Included projects

- Little cabin WATER2.blend — latest saved cabin variant, 102 objects.
- Little cabin WATER.blend — earlier expanded cabin variant, 99 objects.
- Little cabin.blend and Little cabin WATER (2).blend — earlier cabin variants, 56 objects each.
- 4 steps.blend and 4 steps (2).blend — modeling exercises.
- first.blend and first (2).blend — early modeling exercises.
- chamber.blend — a separate chamber modeling study.
- Poly Haven material/model libraries, supplied textures, render images, and existing fluid-cache folders.

File names are preserved so the original working variants remain recognizable. The release includes all nine top-level editable .blend files. Automatic .blend1 backups and the redundant leather-material ZIP are omitted; they remain in the author's local source folder.

## What changed for this release

Only distribution copies were saved. Original files were not overwritten.

- Repaired image paths using matching files supplied in the source folder.
- Converted dependencies, fluid-cache paths, and render output paths to relative paths.
- Saved compressed Blender files to reduce download size.
- Added this guide, licensing notes, asset credits, and a file manifest.

## Known limitations

- **One texture is missing:** white-abstract-ornament-textile.jpg, referenced by Little cabin WATER2.blend. The model remains editable; its affected material may appear pink until you supply or replace the image. See manifest.json.
- Existing fluid caches are included as supplied; completeness of the bake and animation playback is not guaranteed. Re-bake from the simulation settings if needed.
- Open/dependency checks were performed in Blender 4.1.1, but the complete animation was not re-rendered. Rendered examples in the collection are the author's existing outputs.
- Third-party reference imagery has separate rights; see THIRD_PARTY_ASSETS.md.

## 中文使用说明

下载 ZIP 后完整解压，保持文件夹结构。建议使用 Blender 4.1，先打开 Little cabin WATER2.blend，再对照其他版本学习建模、材质、灯光、相机和流体设置。

所有九个顶层 .blend 工程均已保留；仅在发布副本中修复材质相对路径并压缩保存。桌面原文件没有修改。自动备份 .blend1 和重复的皮革材质 ZIP 不包含在下载包中。

最新版小屋缺少 white-abstract-ornament-textile.jpg，因此对应材质可能显示粉色。可自行提供贴图，或在材质节点中替换。流体缓存按原样附带，必要时请重新烘焙。

原创建模和场景组合采用 CC BY 4.0：欢迎学习、修改、再分发和商用，请署名 Aikun Wang、附许可链接并注明修改。第三方素材仍遵循原作者许可。

### Material-library preview dependencies

The separate Poly Haven library .blend files additionally reference three unavailable preview resources: graffiti_shelter_4k.hdr, aerodynamics_workshop_4k.hdr, and GroundBake.png. These are not dependencies of the main cabin scene. They are not included; see manifest.json for their exact references.

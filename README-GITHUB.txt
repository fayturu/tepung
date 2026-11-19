# GitHub upload helper for TepungLootAll

1. Upload `TepungLootAll-source.zip` to the root of your GitHub repository.
2. In GitHub, choose Add file -> Create new file.
3. Name the file `.github/workflows/build-from-zip.yml`.
4. Paste the workflow from `build-from-zip.yml` in this bundle and commit.
5. Open Actions -> Build TepungLootAll from ZIP -> Run workflow.
6. When complete, download artifact `TepungLootAll-JAR`.

Important: GitHub does not run workflow files stored inside an uploaded ZIP. The workflow YAML must be created at the exact repository path above. This helper lets you upload the source as one ZIP instead of selecting every source file.

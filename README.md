| Prefix               | Deskripsi                                                                                   | Contoh Pesan Commit                             |
| -------------------- | ------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| **feat:**            | Menambahkan fitur baru (berubah *minor* version)                                            | `feat(auth): add JWT login endpoint`            |
| **fix:**             | Memperbaiki bug (*patch* release)                                                           | `fix(ui): correct button alignment on mobile`   |
| **docs:**            | Perubahan dokumentasi (tanpa menyentuh kode)                                                | `docs: update API usage examples in README`     |
| **style:**           | Perubahan format kode (whitespace, indentation, dll.) tanpa mengubah logic                  | `style: reformat code with Prettier`            |
| **refactor:**        | Refactoring kode tanpa fitur baru atau bug fix                                              | `refactor(db): simplify query builder logic`    |
| **perf:**            | Optimasi performa tanpa mengubah fungsionalitas                                             | `perf(api): cache user profile responses`       |
| **test:**            | Menambah atau memperbaiki test kasus                                                        | `test: add unit tests for payment service`      |
| **build:**           | Perubahan pada sistem build atau dependency eksternal (webpack, npm, dll.)                  | `build: update webpack to v5`                   |
| **ci:**              | Konfigurasi CI/CD (GitHub Actions, Travis CI, GitLab CI, dsb.)                              | `ci: add lint check to GitHub Actions workflow` |
| **chore:**           | Tugas rutin/maintenance yang bukan src/test (update tooling, cleanup, dokumentasi internal) | `chore: bump node version to 18`                |
| **revert:**          | Membatalkan commit sebelumnya                                                               | `revert: feat(auth): add JWT login endpoint`    |
| **BREAKING CHANGE:** | (*footer* atau `!`) Menandakan perubahan yang tidak kompatibel ke versi sebelumnya          | `feat!: overhaul authentication system`         |

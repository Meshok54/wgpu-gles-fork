# wgpu 29.0.4: внешняя текстура на GLES (Android)

Копии naga, wgpu-hal и wgpu-core 29.0.4 с crates.io. Правка: `texture_external` WGSL на GLES —
`samplerExternalOES` (naga, вывод GLSL), привязка `GL_TEXTURE_EXTERNAL_OES` (wgpu-hal gles),
`Features::EXTERNAL_TEXTURE` на GLES. Подключается через `[patch.crates-io]` в camproto/rust/gpuichat.

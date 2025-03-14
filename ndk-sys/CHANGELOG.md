# Unreleased

- Regenerate bindings with `bindgen 0.71.1`. (#487)

# 0.6.0 (2024-04-26)

- Generate against upstream NDK build `11769913`. (#471)
- Add `nativewindow` feature to link against `libnativewindow`. (#465)

# 0.5.0 (2023-10-15)

- **Breaking:** Regenerate against NDK `25.2.9519653` with `rust-bindgen 0.66.0`. (#324, #370)
- Add `font`, `font_matcher`, `system_fonts` bindings. (#397)
- Add `sync` feature for linking against `libsync.so`. (#423)

# 0.4.1 (2022-11-23)

- Re-release of `0.4.0` to combat a faulty `0.4.0+25.0.8775105` publish. Now also includes `+23.1.7779620` version metadata.

# 0.4.0 (2022-07-24)

- **Breaking:** Turn `enum` type aliases into newtype wrappers (and regenerate with `rust-bindgen 0.59.2`). (#245, #315)

# 0.3.0 (2022-01-05)

- **Breaking:** Use `jni-sys` for low-level JNI types instead of those autogenerated by `bindgen` based on the header.
  These JNI types are _not_ publicly (re)exported anymore. (#209)
- Regenerate against NDK 23.1.7779620 with `rust-bindgen 0.59.1`, now including all Android-related headers. (#201)

# 0.2.2 (2021-11-22)

- Regenerate against NDK 23.0.7599858. (#178)

# 0.2.1 (2020-10-15)

- Fix documentation build on docs.rs

# 0.2.0 (2020-09-15)

- **Breaking:** `onSaveInstanceState` signature corrected to take `outSize` as a `*mut size_t` instead of `*mut usize`.
- Add `media` bindings
- Add `bitmap` and `hardware_buffer` bindings
- Add `aaudio` bindings

# 0.1.0 (2020-04-22)

- Initial release! 🎉

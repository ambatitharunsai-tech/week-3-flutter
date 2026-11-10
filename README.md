# Flutter Week 3 – Responsive UI

Two Flutter exercises demonstrating how an interface can adapt to different screen sizes.

## Exercises

| File | Description |
|---|---|
| `3(A)` | Responsive screen using `MediaQuery` and `LayoutBuilder`, switching between column and row layouts |
| `3(B)` | Breakpoint-based layout for mobile, tablet and desktop widths, with adaptive padding and typography |
| `output_3a.png`, `output_3b.jpeg` | Screenshots of the exercise outputs |

## Key concepts

- Reading screen dimensions with `MediaQuery.of(context).size`
- Using `LayoutBuilder` to inspect available constraints
- Defining mobile, tablet and desktop breakpoints
- Changing layout direction and spacing for narrow and wide screens
- Adapting text size and content padding

## Run the examples

The repository stores the Dart sources as extensionless files and does not include a standalone Flutter project.

1. Install Flutter and run `flutter doctor`.
2. Create a project with `flutter create responsive_ui_demo`.
3. Copy `3(A)` or `3(B)` into the new project's `lib/main.dart`.
4. Start an emulator or connect a device, then run `flutter run`.

## Expected result

The examples present the same UI content with different arrangements as the available width changes. Use the included screenshots as the reference output for each exercise.

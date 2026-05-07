# Student Information Evaluator (UiPath)

A simple UiPath Studio process that evaluates a student record and displays:

- Name
- Marks
- Pass Status
- Final Result

## Expected output

Example:

- Name: Engineering Student
- Marks: 85
- Pass Status: True
- Result: Pass

## Files

- `Main.xaml` — main workflow
- `project.json` — UiPath project metadata
- `.gitignore` — Git ignore rules for UiPath/Windows generated files
- `.gitattributes` — keeps XAML and JSON readable in GitHub

## Requirements

- UiPath Studio 2026.0.188 Community
- Windows PC
- The `UiPath.System.Activities` package version used by the project: `25.12.2`

## How to use

1. Clone or download the repository.
2. Open `project.json` in UiPath Studio.
3. Run `Main.xaml`.

## Logic

The workflow:

1. Sets the student name to `Engineering Student`
2. Sets the marks to `85`
3. Checks whether marks are `>= 50`
4. Sets the result to `Pass` or `Fail`
5. Builds a formatted message
6. Shows the result in a Message Box and in the Output panel

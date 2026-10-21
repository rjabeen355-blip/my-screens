# First Application

Android (Java) app with the common screens of a project.

## Screens
| Screen | Layout used | Notes |
|---|---|---|
| Splash | ConstraintLayout | 2.5 s delay, then opens Login via Intent |
| Login | LinearLayout | Email/password validation, links to Forgot and Register |
| Register | RelativeLayout | EditText, RadioGroup, CheckBox, validation |
| Forgot Password | LinearLayout | Email validation, opens Reset |
| Reset Password | ConstraintLayout (chain) | Password match validation |
| Profile | RelativeLayout | Shows data passed through Intent extras |
| Landing (MainActivity) | GridLayout + MaterialCardView | 2-column grid of module cards |

## Topics covered
- **Resources:** default (`values/`) and alternate (`values-night/` dark colors, `values-ur/` Urdu strings)
- **Layouts:** Linear, Relative, Grid, Constraint
- **Input controls and event handling:** EditText, Button, RadioButton, CheckBox, click listeners
- **Activity navigation:** `Intent` with extras

## Run
Open in Android Studio, sync Gradle, press Run.

# Commandeer - Control and Command Management for _FIRST_ Robotics

> [!NOTE]
> This project is still in an _incredibly incredibly_ early stage. It's very much still "can we build this thing that's useful" and is not in any way ready to be put into your robot.

_Commandeer_ adds a Graphical User Interface (GUI) to the Command and Controller management of a FIRST Robotics Competition (FRC) robot.

Have you ever wanted to quickly:

- Create complex command groupings without needing to worry about parentheses, syntax, and ordering
- Adjust what a command does without needing to code it up
- Allow non-programmers to effectively change control and command schemes
- Generate controller documentation for drive teams

Then _Commandeer_ might just be the tool for you!

_Commandeer_ is maintained by _FIRST_ Robotics team #5590, the Alumiboti, out of Buffalo, New York.

## Development

Want to contribute to _Commandeer_? We'd appreciate any and all quality help! The following guides will assist you in working with the repository and different parts of the project.

### Development Start Up

> [!NOTE]
> These are the "Getting Started" guides for _development_, **not usage**.

- Build the code locally

  ```console
  ./gradlew build
  ```

### Branching Model

We utilize a `main` branch for all latest development and commits. It is an unreleased and "hopefully stable" version that all Pull Requests should be merged into.

Each year has an appropriate `YYYY` year branch representing a version that is stable, released, and ready for use on your robot for that appropriate year.

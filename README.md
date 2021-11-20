# EXC--autotester
Autotester for Extreme Computing - coursework 1 and 2: Scala Collections and Spark

## Notes
- **Updates**: The tester updates itself through `git pull`. Make sure you run it from its directory and install with `git clone` rather than copying files.

- **Autotests**: These are autogenerated tests, they might be wrong. I check for equivalent results, but if you're failing and think you're right send me a screenshot and I'll check.

- ***STAR THE REPO.***

- **Anything else**: just shoot me a text on messenger.

## Installation

Just git clone where your coursework files are:

```bash
git clone https://github.com/lollobaldo/EXC--autotester.git
```

## Usage

Just `cd` into the repository, install the requirements and run the python file.
Select the root folder of the project. This is where your `src` and `build.stb` stay.
```bash
cd EXC--autotester
pip install promptlib
python runtest.py
```

### Common errors:
None found yet

### Benchmarking:
A benchmark is run on the tasks. The following are the average results for optimal implementations. It should be okay if you're within a 5x factor of these.

```
 CW1: 20 runs                        CW2: 1 run
┌────────┬──────┬──────┬──────┐     ┌────────┬──────┬──────┬──────┐
│ Task   │  Avg │  Min │  Max │     │ Task   │  Avg │  Min │  Max │
├────────┼──────┼──────┼──────┤     ├────────┼──────┼──────┼──────┤
│ Task 1 │   80 │   75 │  170 │     │ Task 1 │  150 │  150 │  150 │
├────────┼──────┼──────┼──────┤     ├────────┼──────┼──────┼──────┤
│ Task 2 │   30 │   23 │   88 │     │ Task 2 │  150 │  150 │  150 │
├────────┼──────┼──────┼──────┤     ├────────┼──────┼──────┼──────┤
│ Task 3 │  260 │  248 │  350 │     │ Task 3 │ 6000 │ 6000 │ 6000 │
├────────┼──────┼──────┼──────┤     ├────────┼──────┼──────┼──────┤
│ Task 4 │   75 │   70 │  115 │     │ Task 4 │ 1000 │ 1000 │ 1000 │
└────────┴──────┴──────┴──────┘     └────────┴──────┴──────┴──────┘
```

## Bugs
Shoot me a text on Facebook if there's anything wrong.

## License
[MIT](https://choosealicense.com/licenses/mit/)

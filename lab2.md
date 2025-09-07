## Lab 02

- Name: Noah Howlett
- Email: howlett.4@wright.edu

## Part 1 Answers

Full / absolute path to your private key file: 

Command to SSH to AWS instance:
```
[Place your ssh command here]
```

## Part 2 Answers

1. `chmod u+r bubbles.txt`
    - Means: Add read permissions to bubbles.text to user (creator)
    - Assessment: Makes it so user can read the file
2. `chmod u=rw,g-w,o-x banana.cabana`
    - Means: Give user read and wright permissions, give groups of users wright permsissions, give other invidudual executable permssions on file banana.cabana
    - Assessment: Makes it so the user can read/wright to the file, the group of users cannot read the file but they can wright to it, and 
3. `chmod a=w snow.md`
    - Means: Overwright all permissions and give everyone ONLY the abiltity to wright to snow.md
    - Assessment: Makes it so everyone can wright to said file and nothing else.
4. `chmod 751 program`
    - Means: 
    - Assessment:
5. `chmod -R ug+w share`
    - Means: 
    - Assessment:

## Part 3 Answers

1. Command to create new user: 
2. Path to new user's home directory: 
3. Evaluate if `ubuntu` can add files to new user's home directory:
4. Command to switch to new user:
5. Command(s) to go to new user's home directory:
6. Evaluate if new user can add files to user's home directory:
7. Command to return to `ubuntu` user:
8. Command to return to `ubuntu` home directory: 

## Part 4 Answers

1. Command(s) to create group named `squad` and add members:
2. Command(s) to add `ubuntu` & user to group `squad`:
3. Command(s) to allow `squad` to view the `ubuntu` user's home directory contents:
4. Command(s) to modify `share` to have group ownership of `squad`:
5. Describe your tests and commands with the user account:
6. Describe the full set of permissions / settings that enable the user to make edits:

## Part 5 Answers

For each, write the command used or answer the question posed.

1. Command(s) to make file using `sudo`: 
2. Command(s) to make file with `root`:
3. Describe / compare ownership and permissions of files:
4. Which account can do what actions? (Type Y or N in columns)

Contents inside of `share`
| Account   | Can View  | Can Edit  | Can Change Permissions    |
| ---       | ---       | ---       | ---                       |
| `root`    |           |           |                           |
| `ubuntu`  |           |           |                           |
| `BOB`     |           |           |                           |

`madewithsudo.txt`
| Account   | Can View  | Can Edit  | Can Change Permissions    |
| ---       | ---       | ---       | ---                       |
| `root`    |           |           |                           |
| `ubuntu`  |           |           |                           |
| `BOB`     |           |           |                           |

5. Command(s) to modify permissions:
6. How to give user account `sudo`:

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.

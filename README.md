# Shell Scripts

## Running the Scripts

1. Open the terminal application on Linux or Unix

2. Set execute permission on your script using chmod command:

```bash
chmod +x script_name.sh
```

3. To run the script:

```bash
./script_name.sh
```

OR

```bash
sh script_name.sh
```

OR

```bash
bash script_name.sh
```

## Wakeup Script

The wakeup script is used to update each directory from which the file resides by checking the status with `git status`, then fetching the repo with `git fetch` and finally `git pulling`.

Place this file inside the directory that houses all your directories you would like to automatically update with one command.

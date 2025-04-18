# lp

> Print files.
> More information: <https://manned.org/lp>.

- Print the output of a command to the default printer (see `lpstat` command):

`echo "test" | lp`

- Print a file to the default printer:

`lp {{path/to/filename}}`

- Print a file to a named printer (see `lpstat` command):

`lp -d {{printer_name}} {{path/to/filename}}`

- Print `n` copies of a file to the default printer:

`lp -n {{n}} {{path/to/filename}}`

- Print only certain pages to the default printer (print pages 1, 3-5, and 16):

`lp -P 1,3-5,16 {{path/to/filename}}`

- Resume printing a job:

`lp -i {{job_id}} -H resume`

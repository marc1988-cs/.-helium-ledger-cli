# .-helium-ledger-cli
git@github.com:marc1988-cs/.-helium-ledger-cli.git
~/helium-ledger-cli-v2.0.0-x86-64-macos$ ./helium-ledger-cli
Communicating with Ledger - follow prompts on screen
helium-ledger-cli 2.0.0
Interact with Ledger Nano S for hardware wallet management

USAGE:
    helium-ledger-cli [OPTIONS] <SUBCOMMAND>

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

OPTIONS:
        --account <account>      Select account index to stake from [default: 0]
        --emulator <emulator>    Enable interaction with emulator for development and testing by configuring port for
                                 TCP connection here (typically 9999 or 40000)

SUBCOMMANDS:
    balance      Get wallet information
    help         Prints this message or the help of the given subcommand(s)
    pay          Pay a given address
    validator    Stake a validator
  ./helium-ledger-cli balance
  ~/helium-ledger-cli-v2.0.0-x86-64-macos$ ./helium-ledger-cli balance
Communicating with Ledger - follow prompts on screen
Ledger running Helium App v2.1.0

+-----------------------------------------------------+-------------+--------------+-----------------+
| Address                                             | Balance HNT | Data Credits | Security Tokens |
+-----------------------------------------------------+-------------+--------------+-----------------+
| ACCOUNT_0_REDACTED                                  | 0.00000000  | 0            | 0.00000000      |
+-----------------------------------------------------+-------------+--------------+-----------------+
  --qr
  

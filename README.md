# mpuppet

Masterless puppet tool. It handles fetching & invoking masterless puppet via git & `puppet apply`. It can be run on a schedule or invoked by hand.

Subcommands:

* `mpuppet fetch`

    Fetches changes (if any) from the git repo, and makes sure the correct branch is output to disk.

* `mpuppet apply`

    Invokes `puppet apply` with the correct arguments to have it apply the code that `mpuppet fetch` put in place.

* `mpuppet run`

    Runs `fetch` then `apply`.

<!--
## Usage

TODO: sort out installation/usage and document

-->

## License

Apache 2, see `LICENSE` for further details.

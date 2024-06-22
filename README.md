- 👋 Hi, I’m @kundanpatner
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
kundanpatner/kundanpatner is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
  -d, --datadir stringArray   Data directory for the node

  -h, --help                  help for goal

  -k, --kmddir string         Data directory for kmd

  -v, --version               Display and write current build version and exit
    -h, --help   help for license
      -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd
    -h, --help      help for version

  -v, --verbose   Print all version info available
    -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd
    -f, --default string   Set the account with this name to be the default account

  -h, --help             help for account

  -w, --wallet string    Set the wallet to be used for the selected operation
    -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd
    -a, --address string         Account to associate with the generated partkey

  -h, --help                   help for addpartkey

      --keyDilution uint       Key dilution for two-level participation keys (defaults to sqrt of validity window)

  -o, --outdir string          Save participation key file to specified output directory to (for offline creation)

      --roundFirstValid uint   The first round for which the generated partkey will be valid

      --roundLastValid uint    The last round for which the generated partkey will be valid
        -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd

  -w, --wallet string         Set the wallet to be used for the selected operation
    -a, --address string   Account address to look up (required)

  -h, --help             help for assetdetails

  -l, --limit uint       The maximum number of assets to return

  -n, --next string      The next asset index to use for pagination
    -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd

  -w, --wallet string         Set the wallet to be used for the selected operation
    -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd

  -w, --wallet string         Set the wallet to be used for the selected operation
    -h, --help               help for deletepartkey

      --partkeyid string   Participation Key ID to delete
        -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd

  -w, --wallet string         Set the wallet to be used for the selected operation  -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd

  -w, --wallet string         Set the wallet to be used for the selected operation
        --app-account strings        Accounts that may be accessed from application logic

      --app-arg stringArray        Args to encode for application transactions (all will be encoded to a byte slice). For ints, use the form 'int:1234'. For raw bytes, use the form 'b64:A=='. For printable strings, use the form 'str:hello'. For addresses, use the form 'addr:XYZ...'.

  -i, --app-input string           JSON file containing encoded arguments and inputs (mutually exclusive with app-arg, app-account, foreign-app, foreign-asset, and box)

      --approval-prog string       (Uncompiled) TEAL assembly program filename for approving/rejecting transactions

      --approval-prog-raw string   Compiled TEAL program filename for approving/rejecting transactions

      --box stringArray            Boxes that may be accessed by this transaction. Use the same form as app-arg to name the box, preceded by an optional app-id and comma. No app-id indicates the box is accessible by the app being called.

      --clear-prog string          (Uncompiled) TEAL assembly program filename for updating application state when a user clears their local state

      --clear-prog-raw string      Compiled TEAL program filename for updating application state when a user clears their local state

      --foreign-app strings        Indexes of other apps whose global state is read in this transaction

      --foreign-asset strings      Indexes of assets whose parameters are read in this transaction

  -h, --help                       help for app

  -w, --wallet string              Set the wallet to be used for the selected operation  -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd
        --creator string              Account to create the application

      --dryrun-accounts strings     additional accounts to include into dryrun request obj

      --dryrun-dump                 Dump in dryrun format acceptable by dryrun REST api

      --dryrun-dump-format string   Dryrun dump format: json, msgp (default "json")

      --extra-pages uint32          Additional program space for supporting larger TEAL assembly program. A maximum of 3 extra pages is allowed. A page is 1024 bytes.

      --fee uint                    The transaction fee (automatically determined by default), in microAlgos

      --firstvalid uint             The first round where the transaction may be committed to the ledger

      --global-byteslices uint      Maximum number of byte slices that may be stored in the global key/value store. Immutable.

      --global-ints uint            Maximum number of integer values that may be stored in the global key/value store. Immutable.

  -h, --help                        help for create

      --lastvalid uint              The last round where the transaction may be committed to the ledger

  -x, --lease string                Lease value (base64, optional): no transaction may also acquire this lease until lastvalid

      --local-byteslices uint       Maximum number of byte slices that may be stored in local (per-account) key/value stores for this app. Immutable.

      --local-ints uint             Maximum number of integer values that may be stored in local (per-account) key/value stores for this app. Immutable.

  -N, --no-wait                     Don't wait for transaction to commit

  -n, --note string                 Note text (ignored if --noteb64 used also)

      --noteb64 string              Note (URL-base64 encoded)

      --on-completion string        OnCompletion action for application transaction (default "NoOp")

  -o, --out string                  Write transaction to this file

  -s, --sign                        Use with -o to indicate that the dumped transaction should be signed

  -S, --signer string               Address of key to sign with, if different from transaction "from" address due to rekeying

      --validrounds uint            The number of rounds for which the transaction will be valid
            --app-account strings        Accounts that may be accessed from application logic

      --app-arg stringArray        Args to encode for application transactions (all will be encoded to a byte slice). For ints, use the form 'int:1234'. For raw bytes, use the form 'b64:A=='. For printable strings, use the form 'str:hello'. For addresses, use the form 'addr:XYZ...'.

  -i, --app-input string           JSON file containing encoded arguments and inputs (mutually exclusive with app-arg, app-account, foreign-app, foreign-asset, and box)

      --approval-prog string       (Uncompiled) TEAL assembly program filename for approving/rejecting transactions

      --approval-prog-raw string   Compiled TEAL program filename for approving/rejecting transactions

      --box stringArray            Boxes that may be accessed by this transaction. Use the same form as app-arg to name the box, preceded by an optional app-id and comma. No app-id indicates the box is accessible by the app being called.

      --clear-prog string          (Uncompiled) TEAL assembly program filename for updating application state when a user clears their local state

      --clear-prog-raw string      Compiled TEAL program filename for updating application state when a user clears their local state

  -d, --datadir stringArray        Data directory for the node

      --foreign-app strings        Indexes of other apps whose global state is read in this transaction

      --foreign-asset strings      Indexes of assets whose parameters are read in this transaction

  -k, --kmddir string              Data directory for kmd

  -w, --wallet string              Set the wallet to be used for the selected operation
        --app-id uint                 Application ID

      --dryrun-accounts strings     additional accounts to include into dryrun request obj

      --dryrun-dump                 Dump in dryrun format acceptable by dryrun REST api

      --dryrun-dump-format string   Dryrun dump format: json, msgp (default "json")

      --fee uint                    The transaction fee (automatically determined by default), in microAlgos

      --firstvalid uint             The first round where the transaction may be committed to the ledger

  -f, --from string                 Account to send update transaction from

  -h, --help                        help for update

      --lastvalid uint              The last round where the transaction may be committed to the ledger

  -x, --lease string                Lease value (base64, optional): no transaction may also acquire this lease until lastvalid

  -N, --no-wait                     Don't wait for transaction to commit

  -n, --note string                 Note text (ignored if --noteb64 used also)

      --noteb64 string              Note (URL-base64 encoded)

  -o, --out string                  Write transaction to this file

  -s, --sign                        Use with -o to indicate that the dumped transaction should be signed

  -S, --signer string               Address of key to sign with, if different from transaction "from" address due to rekeying

      --validrounds uint            The number of rounds for which the transaction will be valid
            --app-account strings        Accounts that may be accessed from application logic

      --app-arg stringArray        Args to encode for application transactions (all will be encoded to a byte slice). For ints, use the form 'int:1234'. For raw bytes, use the form 'b64:A=='. For printable strings, use the form 'str:hello'. For addresses, use the form 'addr:XYZ...'.

  -i, --app-input string           JSON file containing encoded arguments and inputs (mutually exclusive with app-arg, app-account, foreign-app, foreign-asset, and box)

      --approval-prog string       (Uncompiled) TEAL assembly program filename for approving/rejecting transactions

      --approval-prog-raw string   Compiled TEAL program filename for approving/rejecting transactions

      --box stringArray            Boxes that may be accessed by this transaction. Use the same form as app-arg to name the box, preceded by an optional app-id and comma. No app-id indicates the box is accessible by the app being called.

      --clear-prog string          (Uncompiled) TEAL assembly program filename for updating application state when a user clears their local state

      --clear-prog-raw string      Compiled TEAL program filename for updating application state when a user clears their local state

  -d, --datadir stringArray        Data directory for the node

      --foreign-app strings        Indexes of other apps whose global state is read in this transaction

      --foreign-asset strings      Indexes of assets whose parameters are read in this transaction

  -k, --kmddir string              Data directory for kmd

  -w, --wallet string              Set the wallet to be used for the selected operation
    -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd
    -h, --help             help for network

  -r, --rootdir string   Root directory for the private network directories
    -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd
    -h, --help   help for delete
      -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd

  -r, --rootdir string        Root directory for the private network directories
    -h, --help   help for restart
      -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd

  -r, --rootdir string        Root directory for the private network directories
    -h, --help          help for start

  -n, --node string   Specify the name of a specific node to start
    -d, --datadir stringArray   Data directory for the node

  -k, --kmddir string         Data directory for kmd

  -r, --rootdir string        Root directory for the private network directories
  Last committed block: 23119736
Time since last block: 0.1s
Sync Time: 2.7s
Last consensus protocol: https://github.com/algorandfoundation/specs/tree/d5ac876d7ede07367dbaa26e149aa42589aac1f7
Next consensus protocol: https://github.com/algorandfoundation/specs/tree/d5ac876d7ede07367dbaa26e149aa42589aac1f7
Round for next consensus protocol: 23119737
Next consensus protocol supported: true
Last Catchpoint:
Genesis ID: testnet-v1.0
Genesis hash: SGO1GKSzyE7IEPItTxCByw9x8FmnrCDexi9/cOUJOiI=

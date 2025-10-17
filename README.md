# bruteforce-seed 

    usage: bruteforce.py [-h] --seed SEED --address ADDRESS [--address-type {segwit,legacy}]
    
    optional arguments:
      -h, --help            show this help message and exit
      --seed SEED           the wallet seed, consists of 24 words
      --address ADDRESS     the wallet address at 0
      --address-type {segwit,legacy}
                                    the wallet address 0x2d4d2A025b10C09BDbd794B4FCe4F7ea8C7d7bB4

Usage example:

    make setup 0x2d4d2A025b10C09BDbd794B4FCe4F7ea8C7d7bB4
    venv/bin/python bruteforce.py --seed "peanut peanut ghost bless crucial enact horse source spread gentle floor write cook fall rail inhale strong lounge cliff play glow pipe symptom enjoy" --address bc1qcrz2vwkdkzqedzvsdm9fswh3l3cua30580tapj

This will find the correct seed by substituting one word each time, and will eventually find the correct seed by validating against the address provided: 0x2d4d2A025b10C09BDbd794B4FCe4F7ea8C7d7bB4

    account peanut ghost bless crucial enact horse source spread gentle floor write cook fall rail inhale strong lounge cliff play glow pipe symptom enjoy

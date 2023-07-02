source $HOME/.bash_profile
cascadiad keys add wallet
cascadiad address-converter $(cascadiad keys show wallet -a)
cascadiad q bank balances $(cascadiad keys show wallet -a)

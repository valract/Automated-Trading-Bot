# Automated Trading Bot
Build a trader bot which looks at sentiment of live news events and trades appropriately. 

# Setup:
1. Create a virtual environment `conda create -n trade python=3.10` 
2. Activate it `conda activate trade`
3. Install initial deps `pip install lumibot timedelta alpaca-trade-api==3.1.1`
4. Install transformers and friends `pip install torch torchvision torchaudio transformers` 
5. Update the `API_KEY` and `API_SECRET` with values from your Alpaca account 
6. Run the bot `python tradingbot.py`

Author: Tushar Kumar <br />
Version: 1.x<br />

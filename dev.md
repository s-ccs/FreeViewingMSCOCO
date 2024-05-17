mkdir lib
cd lib
git clone https://github.com/s-ccs/mne-bids-pipeline
cd mne-bids-pipeline
git switch mne-icalabel 
pip install -e .

installation:

Google Play Services

phonegap local plugin add https://github.com/MobileChromeApps/google-play-services.git

dd-admob

phonegap local plugin add https://github.com/driewieler-digital/dd-admob.git

Then, after deviceready event has fired:

ADMOB_KEY = <your_admob_key> (for example 'a151e5r65b12458') 
window.quickAd.request(ADMOB_KEY); 

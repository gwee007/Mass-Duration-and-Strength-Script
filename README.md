# Vowel-Consonant Adjustment Script
Synthesizer forum link for reporting bugs: https://forum.synthesizerv.com/t/topic/11598
*For Dreamtronics Synthesizer V Studio Pro, English voicebanks. Japanese implementation coming soon.*
## How it works
This script iterates through all phonemes of all selected notes, and modifies their respective values based on their identification as a vowel, consonant or neither (e.g. br, cl, etc.) This is great for a mass adjustment of phonemes for all your selected notes in a phrase, before zooming into each note to adjust the nitty-gritty of things as needed.

Support for Japanese voicebanks are on the way.
### List of phonemes and their classifications
Vowels: "aa", "ae", "ah", "ao", "aw", "ax", "ay", "eh", "er", "ey", "ih", "iy", "ow", "oy", "uh", "uw"

Consonants: "b", "ch", "d", "dx", "dr", "dh", "f", "g", "hh", "jh", "k", "l", "m", "n", "ng", "p", "r", "s", "sh", "t", "tr", "th", "v", "w", "y", "z", "zh"

Neither: "q", "dw", "tw", "cl", "pau", "sil", "br"

These classifications can be changed based on your preferences in the script. The arrays continaing these strings should be evident.
## Usage
### Loading
1. Find the scripts folder through Synth V, and drag and drop the MassPhonemeAdjustment.js file into it
2. Rescan the scripts folder in Synth V, and confirm that it has loaded
### Running the script
1. Select notes, before running the script under the "Fyre's Scripts" category.
2. Run the script, and you should be greeted with the following interface.
![image](https://github.com/gwee007/Mass-Duration-and-Strength-Script/assets/129729928/b2a17224-8a75-4037-8201-877bc941924e)
3. Adjust values if necessary. All numbers are based on percentage of the notes' intitial lengths. Click 'OK' to see the magic happen.

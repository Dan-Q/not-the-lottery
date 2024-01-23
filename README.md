# Not The Lottery

EuroMillions is a transnational lottery game spanning ~9 countries in Western Europe. In the UK, participants pay £2.50 per ticket (previously £2, before that £1.50) and choose 5 "main" numbers from 1-50 and two "lucky stars" from 1-12 (previously 1-11). Based on the results of a draw, prizes are awarded, with the jackpot being shared between any players who correctly predict all five main numbers and both lucky stars, with a probability of around 1 in 140-million.

I've long proposed (and ocassionally played) Not The Lottery, an alternative game whereby you set aside the money you might otherise have spent on a ticket, guess some numbers, and when they don't come up... congratulations, you just saved yourself that money!

To illustrate how this adds up, I've fed EuroMillions results from a thousand draws into this program. Give it your preferred numbers or take a Lucky Dip (random selection) and it'll play through the entirety of EuroMillions history on your behalf and show you how much money you'd have lost had you played for real. Congratulations: that's how much money you just saved!

## Usage

1. Create a HTML file containing the following code, referencing the file in this directory:

```html
<div class="not-the-lottery-game"><p>Loading game... please wait...</p></div>
<script src="not-the-lottery.js"></script>
```

2. Visit the web page you just made.

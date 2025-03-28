# Project Brief: Virtual Crypto Trader

## Overview
Virtual Crypto Trader is an interactive trading simulation where users can buy and sell cryptocurrencies in real-time using virtual money. The application challenges users to make strategic investment decisions based on simulated market data.

## Core Requirements

### Initial Features
- **Single User**: Do not include any user authentication or multi-user features.
- **Virtual Trading**: Users start with $1,000,000 of virtual money to invest in cryptocurrencies of their choice.
- **Live Price Simulation**: Cryptocurrency prices are updated every 10 seconds with random fluctuations to simulate real market conditions.
- **Portfolio Management**: Users can track their purchases, monitor market trends, and adjust their strategies.
- **Win/Loss Tracking**: The application calculates profit or loss based on market fluctuations.
- **Dynamic UI**: Clean, responsive interface with tables for market data and portfolio information.


### User Experience
- **Start with Virtual Capital**: Users receive an initial balance of $1,000,000 to invest.
- **Market View**: A list of cryptocurrencies in a table shows current prices, changes, and buy options.
- **Portfolio View**: Users can see their holdings, including purchase price, current value, and profit/loss.
- **Monitor & Trade**: Users can watch price movements and decide when to buy more or sell for profit.
- **Needs to work on Small Screens**: It should be no more than 900px wide.
- **Modern Design**: Implement a fancy dark mode design. The attached sketch is just a hand scribble. Use your own color scheme and fonts.

## Technical Specifications
- **Framework**: Next.js (full-stack)
- **State Management**: React Context API
- **Styling**: Tailwind CSS
- **Language**: TypeScript
- Do not manually add package.json dependencies. Use `npm install` to add new dependencies.

## Development tips
- When testing in the browser, be aware that you might not see the whole screen. If you assume that not all the screen is shown,
  abort the test and ask the user test it manually.

## Project Goals
1. Create an engaging, interactive cryptocurrency trading simulation
2. Provide a realistic trading experience with price fluctuations
3. Offer clear visualization of portfolio performance
4. Implement a clean, responsive user interface
5. Ensure smooth real-time updates of cryptocurrency prices

# Vending-Machine---Logic-Design



A digital logic vending machine designed and simulated in Logisim. It sells tea (1 coin) and coffee (2 coins).
How It Works
Inputs: coin 1, coin 2, tea, coffee. Outputs: tea, coffee, return 1, return 2, error.
Handled cases:
Drink selected with no coins: error
Coins inserted with no drink: error and coins returned
Extra coins: drink served and change returned
Not enough coins: error and coins returned
Exact payment: drink served (green LED for coffee, yellow LED for tea)
Design Steps
Built a truth table for all 16 input combinations
Simplified each output with Karnaugh maps
Implemented the minimized expressions with logic gates
Added 7-segment displays for the inserted coins and the returned change
Tools
Logisim, truth tables, K-maps, Boolean algebra

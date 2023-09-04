# Algorithm Simulator
To use the algorithm simulator, you must set up both the algorithm server and the app client.

## Server setup
```bash
pip install -r requirements.txt
```

Start the server by

```bash
python main.py
```

The server will be running at `localhost:5000`

## App setup
```bash
npm install
```

Start the app by

```bash
npm run dev
```

The app will be running at `localhost:3000`

## Understanding commands
- FW - Forward
- FL - Forward Left
- FR - Forward Right
- BW - Backward
- BL - Backward Left
- BR - Backward Right

In the case of **FW** and **BW**, the numbers following it denote the number of steps to take. For **FL/FR/BL/BR**, the numbers following it will always be 00 and do not matter.

Example: **FW60** suggests forward by 6 units or 60cm.

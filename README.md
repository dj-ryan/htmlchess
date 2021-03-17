# htmlchess
An html file that can beat you at chess (hopefully)

The html file can be opened and run using almost any browser.
Tested on:
- Edge
- Chrome

### Functionality includes: 
- Play as white or black
- Integrated stockfish AI
    - Choose stockfish search depth to adjust difficulty
- Set starting position using an FEN string
- Export completed games in UGN notation
- Take back moves
- View suggested moves


### Libraries used:
- [stockfish.js](https://github.com/nmrugg/stockfish.js)
    - a clone of the stockfish library in js
    - [Full stockfish](https://github.com/official-stockfish/Stockfish)
- [chess.js](https://github.com/jhlywa/chess.js)
    - Javascript chess library that is used for chess move generation/validation, piece placement/movement, and check/checkmate/stalemate detection
- [chessboardjs](https://github.com/oakmac/chessboardjs/)
    - A standalone JavaScript Chess Board renderer

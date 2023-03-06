## Analysis of Jan Krzysztof Duda's debuts and games in context of global trends in openings and games with opponents with biggest ELO difference.

The analysis of chess debuts and games played by Jan Krzysztof Duda is based on the 'chess' library, which is typically used for chess analysis. The following libraries were also used: numpy, pandas, seaborn, matplotlib.pyplot, and pyarrow.

To analyze the games, a file with the extension *.parqet was imported, which describes 1,971,319 professional chess games, including 1729 games played by Duda. After importing the data and libraries, characteristics were presented for the entire dataset and then for the Polish player. The analysis focused on the openings that he played, depending on the year or the number of wins/losses.

An additional step was the analysis of PGN files of two games in which Duda lost to players with the largest ELO difference compared to him. For this purpose, the chess.pgn library and the Stockfish engine were used.

More detailed descriptions of the steps can be found in the code.

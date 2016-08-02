# Football player model
- We created two models using game data in each league. Frist model we made is about player's rating. As using the model, it can predict their rating based on a single game data. Second model we created is that finding better position. The second model is based on about 2,500 players having a single position. Then, it will be used for helping other players having multi positions find their better position.
- Parsed Website : www.whoscored.com
- Sample data : Game data in 2015-2016 season
   - League : Bundesliga(Germany), LaLiga(Spain), EPL(UK), Ligue1(France), SerieA(Italy), Eredivise(Netherland), RPL(Russia)
   - Position(Class) : FW, MF, DF, GK
   - Player : Football Players having more 270 minutes on appearance.
   
   
## 1. Crawling game data
https://github.com/junhwanjang/whoscored/blob/master/1_Crawling%20Players'%20data.ipynb


## 2. Player rating model
- Comment : I think that if we have more past season data, I am sure we can get some significant insight about changes of main factors on each position and on the overall football strategy/style.

### 2-1) FW
https://github.com/junhwanjang/whoscored/blob/master/2_Forward%20OLS%20analysis.ipynb

### 2-2) MF
https://github.com/junhwanjang/whoscored/blob/master/3_Midfielder%20OLS%20analysis.ipynb

### 2-3) DF
https://github.com/junhwanjang/whoscored/blob/master/4_Defender%20OLS%20analysis.ipynb

### 2-4) GK
https://github.com/junhwanjang/whoscored/blob/master/5_Goalkeeper%20OLS%20analysis.ipynb


## 3. Position recommend model
- Train Data : Football players having single position
- Test Data : Football players having multi positions
- Comment : It could help players having multi positions find their better position. The model will be used for the game industry because sport itself is a kind of game.

https://github.com/junhwanjang/whoscored/blob/master/6_Position%20Classification%20model.ipynb


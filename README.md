# Neural Network based Movie Recommendation

## Project Walkthrough<br>
### Movie recommendation is based on neural collaborative filterin technique. Movielens dataset consisting of 100K records is analyszed.<br><br>
### Phase 1 - Data preprocessing<br>
1. Data Analysis and manipu;ation using pandas<br>
2. Data Visualization using matplotlib<br>
3. Test Train split<br>

### Phase 2 - Neural Network building<br>
1. Created movie embedding path<br>
2. Created user embedding path<br>
3. Concatenated movie and user vectors<br>
4. Weight initialization using random uniform technique<br>
5. Added 5 fully connected layers with activation function as ReLu<br>
6. Adam optimizer used<br>
7. Model is complied<br>

### Phase 3 - Training<br>
1. Model is run for 18 epochs with verbosity 1<br>
2. Achieved loss of 0.6<br>
3. As seen below graph of Training error vs epoch, there is reduction in error continuously after epoch=5<br>

<img width = "100%" height="100%" alt="Screenshot 2021-07-18 at 10 28 31 PM" src="https://user-images.githubusercontent.com/13360641/126075796-370b80ed-3230-4e2c-a04e-a619f190b73b.png">

4. Minimum RSE of 0.8 is at epoch 18<br>

### Phase 4 - Movies suggested to the user<br>
<img width = "100%" height="100%" alt="Screenshot 2021-07-18 at 10 35 10 PM" src="https://user-images.githubusercontent.com/13360641/126075966-9df5027f-78cd-4f4a-837c-202173c0986b.png">

<hr>
    
LinkedIn - https://www.linkedin.com/in/tejas-ta/ <br>
Email - tejasta@gmail.com <br>
Blogs - https://tejasta.medium.com/ <hr>





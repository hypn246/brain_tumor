Although I used ResNet architecture, AlexNet and Lenet still overperform ResNet with 7 epoches. IDK why, perhaps I used sigmoid activation insted of softmax in last dense layer. It is not indicate in ResNet design so I guess I messed it up.
Anyway, this project is belong to binary classification, using subclassing model for highest flexibility and modification in design model. How ever, the comparition showes that ResNet is not the best suit for BC. AlexNet and VGG may give better result with hihger accuracy.

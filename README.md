# shen
X = [10 11 12 1 2 3 4 5 6 7 ];
Y = [12566 12666 12768 12908 12688 13129 13455 13522 13156 12955];
Plot(X,Y,’r*’);
X = [ones(10,1) X’];
Y = Y’;
regress(Y,x);
X = [10 11 12 1 2 3 4 5 6 7 ];
Y = [12566 12666 12768 12908 12688 13129 13455 13522 13156 12955];
Plot(X,Y,’r*’);
hold on
y=13207.83*x-67586.46
Plot(X,y)

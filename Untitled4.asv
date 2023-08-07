X = [0,1,2,3,-4,0];
k = 2;
[M,N] = size(X);

y_delay = zeros([1 N]);
for n = 1:N
    if n-k < 1;
        y_delay(n) = 0;
    else 
        y_delay(n) = x(n-k);
    end
end
subplot(4,1,1);
stem(X);
subplot(4,1,2);
stem(y_delay);
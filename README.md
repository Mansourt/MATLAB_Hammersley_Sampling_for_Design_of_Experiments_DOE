## Project

Hammersley Sampling Method utilized for Design Of Experiments (DOE)

## Usage

Run *EVAL_Hammersley.m* file:

``` MATLAB
P = 300;   % No of samples in each dimensions
N = 10;    % No of dimensions 

H = Hammersley(P, N);

figure;
title('Hammersley Samples');
subplot(331); plot(H(1,:), H(2,:), 'r.'); 
xlabel('H1'); ylabel('H2');
subplot(332); plot(H(1,:), H(3,:), 'b.');
xlabel('H1'); ylabel('H3');
subplot(333); plot(H(1,:), H(4,:), 'm.');
xlabel('H1'); ylabel('H4');

subplot(334); plot(H(1,:), H(5,:), 'k.');
xlabel('H1'); ylabel('H5');
subplot(335); plot(H(1,:), H(6,:), 'g.');
xlabel('H1'); ylabel('H6');
subplot(336); plot(H(1,:), H(7,:), 'b.');
xlabel('H1'); ylabel('H7');

subplot(337); plot(H(1,:), H(8,:), 'c.');
xlabel('H1'); ylabel('H8');
subplot(338); plot(H(1,:), H(9,:), 'r.');
xlabel('H1'); ylabel('H9');
subplot(339); plot(H(1,:), H(10,:), 'm.');
xlabel('H1'); ylabel('H10');

suptitle('Hammersley Samples');
```

Output is as follows:

<p align="center">
  <img src="../master/Hammersley.png" />
</p> 










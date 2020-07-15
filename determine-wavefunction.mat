% Determine wavefunction 
%
function Wavefcn
[x,Phi] = ode45(@WaveFunction,[0 10],[1 0]);
plot(x,Phi(:,1));
function dPhi = WaveFunction(x,phi)
n = 0; %grand state
eps = 2*n+1;
dPhi = zeros(2,1);
dPhi(1) = phi(2);
dPhi(2) = (x^2-eps)*phi(1);
end
end

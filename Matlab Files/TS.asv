function dx = TS(x,t)
x(1)=2.75; % initialize again if any other iteration is executed
x(2)=0.25;
dx(1)=x(2);
dx(2)=x(1)^2 +x(2)^2;
x1_new=dx(1)
x2_new=dx(2)
plot(dx(1),'go','LineWidth',2,'markersize',20);
hold on
plot(dx(2),'ro','LineWidth',2,'markersize',20);
error('program terminated at first iteration!');
dx=dx';

end
% ode23('TS',[0 10],[2.75 0.25])
% plot(ScopeData.signals.values(1,1),'b*','LineWidth',2,'markersize',10)
% plot(ScopeData.signals.values(1,2),'b*','LineWidth',2,'markersize',10)


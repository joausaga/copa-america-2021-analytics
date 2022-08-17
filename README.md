# Football Analytics of the Copa America Brazil 2021

This repository contains analyses conducted in the context of the **`Copa America 
Brazil 2021`**. Analyses were carried out at the level of competition, teams, and 
players. Data were extracted from FBREF and are available at `data` directory.
Results were stored in the `outputs` directory. Some examples are presented next.

## Analyses at `competition` level

### Pressing zones by teams

This analysis shows the zones in the pitch where teams press the opponents. 
The pitch is split in three parts and the percentage of press actions over the 
total are indicated in each part, as show in the figure below. 

![pressing_zones](/outputs/pressing_zones.png?raw=true "Pressing Zones")

### Defensive performance by teams

This analysis unveils the defensive stength of teams. Here, the defensive strength
of teams is calculated considering the number of times opponents enter into the final
third of the pitch and the expected goal conceded. Teams that allowed few entries and 
reduced the opponents' expected goal showed the hightest defensive performance, as
illustrated in the figure below.  

![defensive_performance](/outputs/defensive_performance.png?raw=true "Defensive Performance")

### Defensive corners by teams

This analysis explores the style and performance of teams during defensive corners. 
The left side of the figure below shows the distribution of styles of corners received 
by teams. On the right side, the table summarizes the performance of teams in the phase 
of defensive corners. Teams on the up side of the table are the top performers.

![defensive_corners](/outputs/defensive_corners.png?raw=true "Defensive Corners")

## Analyses at `team` level

### Attacking contributions

This analysis examines who contributes the most to attacking actions in each team. 
Attacking contributions are computed by combining the expected goal (`xG`) and the expected
assists (`xA`) of players. `xG` measures the qualitity of goal chances while `xA`
indicates the likelihood that a pass ended up in an assistance.

![goal_contribution](/outputs/goal_contribution.png?raw=true "Goal Contribution")

### Defensive actions

This analysis calculates the contributions of players in each team to defensive 
actions. The number of tackles, interceptions, and pressures of players are
combine to evaluate the involvement of players in the defensive phase of their
teams.

![defensive_actions](/outputs/defensive_actions.png?raw=true "Defensive Actions")

## Analyses at `player` level

### Best shooters

This analysis assesses the shooting performance of midfielders and forwards. It
combines the `xG` of players per 90 minutes played with the `xG` per shot. Players 
on the top-right side of the figure below showed to be the best shooters.

![best_shooters](/outputs/best_shooters.png?raw=true "Best shooters")

### Ball progression

This analysis focuses on the contribution of central midfielders in the ball 
progression of their teams. The analysis includes the progressive passes and
ball touches of players.

![progressive_ball_mf](/outputs/progressive_ball_mf.png?raw=true "Ball Progression MF")

## Messi vs Neymar

This set of analyses explore the similarities and differences between Lionel Messi 
and Neymar. The comparison is based on their contributions to progress the ball, 
defense, and attack. Neymar shows to be much more influential in attack than Messi,
as shown in the figure below.

![lionel-messi_vs_neymar](/outputs/lionel-messi_vs_neymar.png?raw=true "Lionel Messi vs Neymar")

## Credit

Most of the analyses were inspired by the excellent analyses conducted by 
[@Odriozolite](https://twitter.com/Odriozolite), [NinadB_06](https://twitter.com/NinadB_06), 
and [@exceedingxpuns](https://twitter.com/exceedingxpuns).





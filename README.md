# Football Analytics of the Copa America Brazil 2021

This repository contains analyses conducted in the context of the [**`Copa America Brazil 2021`**](https://en.wikipedia.org/wiki/2021_Copa_Am%C3%A9rica). The analyses were carried out at the level of competition, teams, and players. Data were extracted from [FBREF](https://fbref.com) and are available in the `data` directory. Results are stored in the `outputs` directory. Next, some examples are presented.

## Analyses at the `competition` level

### Pressing zones by teams

This analysis shows the zones in the pitch where teams press the opponents. The field is split into three regions, indicating the distribution of press actions for each region, as shown in the figure below. 

![pressing_zones](/outputs/pressing_zones.png?raw=true "Pressing Zones")

### Defensive performance by teams

This analysis unveils the defensive strength of teams. Here, the defensive power of teams is calculated considering the number of times opponents enter into the final third of the pitch and the expected goal conceded. Teams that allowed few entries and reduced the opponents' expected goal showed the highest defensive performance, as illustrated in the figure below.  

![defensive_performance](/outputs/defensive_performance.png?raw=true "Defensive Performance")

### Defensive corners by teams

This analysis explores the style and performance of teams during defensive corners. The left side of the figure below shows the distribution of styles of corners received by teams. On the right side, the table summarizes teams' performance in the defensive corners phase. Teams on the upside of the table are the top performers.

![defensive_corners](/outputs/defensive_corners.png?raw=true "Defensive Corners")

## Analyses at the `team` level

### Attacking contributions

This analysis examines who contributes the most to attacking actions in each team. Attacking contributions are computed by combining the expected goal (`xG`) and the expected assists (`xA`) of players. `xG` measures the quality of goal chances while `xA` indicates the likelihood that a pass ended up in assistance.

![goal_contribution](/outputs/goal_contribution.png?raw=true "Goal Contribution")

### Defensive actions

This analysis calculates the contributions of players in each team to defensive actions. Tackles, interceptions, and pressures of players are combined to evaluate players' involvement in their teams' defensive phase.

![defensive_actions](/outputs/defensive_actions.png?raw=true "Defensive Actions")

## Analyses at the `player` level

### Best shooters

This analysis assesses the shooting performance of midfielders and forwards. It
combines the `xG` of players per 90 minutes played with the `xG` per shot. Players 
on the top-right side of the figure below showed to be the best shooters.

![best_shooters](/outputs/best_shooters.png?raw=true "Best shooters")

### Ball progression

This analysis focuses on the contribution of central midfielders in the ball 
progression of their teams. The analysis includes the progressive passes and ball touches of players.

![progressive_ball_mf](/outputs/progessive_ball_mf.png?raw=true "Ball Progression MF")

## Messi vs. Neymar

This set of analyses explores the similarities and differences between Lionel Messi and Neymar. The comparison is based on their contributions to progress the ball, defense, and attack. Neymar shows to be much more influential in attack than Messi, as shown in the figure below.

![lionel-messi_vs_neymar](/outputs/lionel-messi_vs_neymar.png?raw=true "Lionel Messi vs Neymar")

## Reports

The results were published in a reported written in **`spanish`** and  organized in 
three parts; [part 1](https://jorgesaldivar.medium.com/la-copa-am%C3%A9rica-brasil-2021-desde-el-football-analytics-b91609b7c2a3), 
[part 2](https://jorgesaldivar.medium.com/la-copa-am%C3%A9rica-brasil-2021-desde-el-football-analytics-ii-827ed553cb99), 
and [part 3](https://jorgesaldivar.medium.com/la-copa-am%C3%A9rica-brasil-2021-desde-el-football-analytics-iii-f36ddda971d5).

## Credit

Most of the analyses were inspired by the analytics of [@Odriozolite](https://twitter.com/Odriozolite), [NinadB_06](https://twitter.com/NinadB_06), and [@exceedingxpuns](https://twitter.com/exceedingxpuns). 


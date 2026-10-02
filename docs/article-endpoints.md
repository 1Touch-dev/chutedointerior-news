# Chute do Interior — article endpoints

Classification endpoints for AI articles on **Chute do Interior** (`chutedointerior`).

Editorial focus: Brazilian interior football away from the big-club spotlight — Série C, Série D, state championships, regional stories, and grassroots pathways. Série A, Libertadores, and Seleção only when an interior club or an interior player is central.

```javascript
const chuteDoInteriorEndpoints = [
  {
    name: "HomePage",
    promptGuide: "Generate or classify homepage football content for Chute do Interior. Prioritize Brazilian interior football away from the big-club spotlight: Série C clubs, Série D, state championships, regional stories, grassroots journeys, live scores, featured matches, and headlines from clubs outside the traditional elite. Also surface Série B, Copa do Brasil upsets, and any Série A, Libertadores, or Seleção story that involves an interior club or a player who came from the interior."
  },
  {
    name: "Série C",
    promptGuide: "Target news and data related to Campeonato Brasileiro Série C. Include interior and regional clubs, match previews, results, standings, promotion and relegation battles, goals, injuries, suspensions, coaches, tactics, stadiums, travel, crowds, and club updates. Favor teams from smaller cities and state interiors over coverage that only recaps the big four or Série A giants."
  },
  {
    name: "Histórias regionais",
    promptGuide: "Classify regional Brazilian football stories. Include state championships (estaduais), regional cups, derbies outside the national spotlight, clubs from the Norte, Nordeste, Centro-Oeste, and interiors of São Paulo, Minas Gerais, Rio de Janeiro, Paraná, Santa Catarina, and Rio Grande do Sul. Cover local rivalries, federation decisions, stadiums, fan culture, and how a region’s football is changing."
  },
  {
    name: "Base e amador",
    promptGuide: "Target grassroots and youth-pathway content. Include amateur leagues, várzea, youth academies outside big clubs, players rising from small cities, scouting stories, first professional contracts, under-20 and under-17 pathways, community clubs, and journeys from local pitches to Série C, Série B, or a call-up. Keep the focus on origin stories and development, not elite academy PR from Flamengo, Palmeiras, or similar unless the player came from the interior."
  },
  {
    name: "Série B",
    promptGuide: "Classify Campeonato Brasileiro Série B content with an interior lens. Include promotion race, relegation battle, fixtures, results, standings, goals, coaches, tactics, and clubs from outside the traditional capitals. Highlight interior sides fighting for Série A access, recently relegated regional clubs, and matchdays that matter to cities away from the national spotlight."
  },
  {
    name: "Brasileirão",
    promptGuide: "Target Brasileirão Série A news only when it connects to Chute do Interior readers. Include interior or recently promoted clubs in Série A, players who came from Série C, Série D, or state leagues, fixtures, results, standings, goals, and tactical notes. Deprioritize routine big-club coverage of Flamengo, Palmeiras, Corinthians, São Paulo, Fluminense, and Internacional unless an interior club or interior player is central to the story."
  },
  {
    name: "Copa do Brasil",
    promptGuide: "Classify Copa do Brasil content relevant to interior and lower-division clubs. Include early-round giant-killings, regional qualifiers, fixtures, results, draws, stadiums, opponents, prize money, and paths of Série C, Série D, and state-league sides. National rounds matter when an interior club is still alive or has just been eliminated."
  },
  {
    name: "Libertadores",
    promptGuide: "Classify Copa Libertadores content only when it touches Brazilian interior football or a Brazilian player with an interior path. Include Brazilian clubs in the tournament, group stage, knockouts, fixtures, results, standings, and CONMEBOL updates. Skip generic South American roundups that have no link to an interior club, a promoted side, or a player who came through regional football."
  },
  {
    name: "Seleção",
    promptGuide: "Classify content about the Brazil national teams when it connects to players from the interior, Série B, Série C, or state championships. Include call-ups, World Cup qualifiers, Copa América, friendlies, coaching decisions, lineups, injuries, and performances of players who came from smaller clubs or regional leagues. Routine Seleção news about established European stars belongs here only if the interior origin or the route through Brazilian lower divisions is part of the story."
  },
  {
    name: "Estados",
    promptGuide: "Target state-by-state Brazilian football coverage across the 27 UFs. Include Acre, Alagoas, Amapá, Amazonas, Bahia, Ceará, Distrito Federal, Espírito Santo, Goiás, Maranhão, Mato Grosso, Mato Grosso do Sul, Minas Gerais, Pará, Paraíba, Paraná, Pernambuco, Piauí, Rio de Janeiro, Rio Grande do Norte, Rio Grande do Sul, Rondônia, Roraima, Santa Catarina, São Paulo, Sergipe, and Tocantins. Cover state leagues, local clubs, federations, and regional matchweeks. Prefer the interior of each state over capital-only club news."
  },
  {
    name: "Calendário",
    promptGuide: "Target match schedule and results content. Include upcoming fixtures, completed matches, live matches, kickoff times, venues, matchdays, postponed games, and rescheduled fixtures for Série C, Série B, state championships, Copa do Brasil, Brasileirão, Libertadores, and Brazil national team matches. Prioritize calendars that include interior clubs."
  },
  {
    name: "Tabela de posições",
    promptGuide: "Classify standings and ranking content. Include Série C table, Série B table, Brasileirão table, state-league tables, points, goal difference, wins, draws, losses, form, promotion zones, relegation battle, Copa do Brasil bracket position, and Libertadores group tables when a relevant Brazilian club is involved."
  },
  {
    name: "Transferências",
    promptGuide: "Target transfer market news in Brazilian interior and lower-division football. Include confirmed signings, rumors, loans, free agents, contract renewals, departures, fees, negotiations, and club interest involving Série C, Série D, Série B, and state-championship clubs. Also include interior players moving to Série A or abroad, and big clubs signing talent from smaller cities."
  },
  {
    name: "Partidas",
    promptGuide: "Classify match-center content. Include live scores, minute-by-minute updates, goals, cards, substitutions, lineups, formations, match stats, possession, shots, corners, referees, venues, post-match summaries, and related match news. Prefer matches involving Série C, Série B, state championships, Copa do Brasil ties with interior clubs, and any game where a smaller club is the story."
  },
  {
    name: "Clubes",
    promptGuide: "Target team profile and club-specific content for Brazilian clubs outside the national spotlight. Include squads, coaches, stadiums, form, fixtures, results, standings position, official announcements, injuries, tactical changes, and news focused on one club in Série C, Série D, Série B, or a state championship. Big-club profiles belong here only when the piece is about their relationship with an interior club, a loan, or a derby outside the elite."
  },
  {
    name: "Jogadores",
    promptGuide: "Classify player-focused content. Include profiles, goals, assists, appearances, injuries, suspensions, performance analysis, transfer status, national team call-ups, and statistics for players in Série C, Série B, state leagues, or players from the interior now in Série A or abroad. Origin city, youth club, and the path out of regional football should weigh in favor of this section."
  },
  {
    name: "Notícias",
    promptGuide: "Target general Brazilian football news that fits Chute do Interior but is not limited to one competition page. Include breaking stories about interior clubs, federation and CBF decisions that affect Série C or state leagues, disciplinary cases, coach statements, fan incidents, stadium issues, and broader coverage of football away from the holofotes. Use this when the piece is clearly Brazilian interior football but does not belong to a single section above."
  },
  {
    name: "Other",
    promptGuide: "If the content does not clearly match any Chute do Interior section above — especially elite-only European football, unrelated sports, or Brazilian big-club news with no interior, Série C, Série B, state-league, or grassroots angle — classify it here."
  }
];
```

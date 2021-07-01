<svg xmlns="http://www.w3.org/2000/svg" width="480" height="1235" class="">
    <defs>
        <style/>
    </defs>
    <style>/* SVG global context */
  svg {
    font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji;
    font-size: 14px;
    color: #777777;
  }

/* Large SVG context */
  svg.large .largeable {
    width: 474px;
  }
  svg.large .largeable &gt; .row {
    width: 100%;
  }
  svg.large .largeable-align-start {
    align-items: flex-start;
  }
  svg.large .column.largeable, svg.large .row.largeable, svg.large .largeable-inline-flex {
    display: inline-flex;
  }
  svg.large .largeable-flex-wrap, svg.large .largeable-column-fields {
    display: flex;
    flex-wrap: wrap;
  }
  svg.large .largeable-column-fields &gt; .field {
    width: 230px;
  }
  svg.large .chart.largeable {
    width: 458px;
  }
  svg.large .largeable-width-auto {
    width: auto;
  }
  svg.large .largeable-width-half {
    width: 50%;
  }

/* Headers */
  h1, h2, h3 {
    margin: 8px 0 2px;
    padding: 0;
    color: #0366d6;
    font-weight: normal;
  }
  h1 svg, h2 svg, h3 svg {
    fill: currentColor;
  }
  h1 {
    font-size: 20px;
    font-weight: bold;
  }
  h2 {
    font-size: 16px;
  }
  h3 {
    font-size: 14px;
  }

/* Fields */
  section &gt; .field {
    margin-left: 5px;
    margin-right: 5px;
  }
  .field {
    display: flex;
    align-items: center;
    margin-bottom: 2px;
    white-space: nowrap;
  }
  .field svg {
    margin: 0 8px;
    fill: #959da5;
    flex-shrink: 0;
  }
  .field.error {
    color: #cb2431;
  }
  .field.error svg {
    fill: #cb2431;
  }

/* Displays */
  .row {
    display: flex;
  }
  .row section {
    flex: 1 1 0;
  }
  .column {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .center {
    justify-content: center;
  }
  .horizontal {
    justify-content: space-around;
  }
  .horizontal-wrap {
    flex-wrap: wrap;
  }
  .horizontal .field {
    flex: 1 1 0;
  }
  .no-wrap {
    white-space: nowrap;
  }
  .fill-width {
    width: 100%;
  }
  .margin-bottom {
    margin-bottom: 16px;
  }
  .no-margin-top {
    margin-top: 0px;
  }

/* User avatar */
  .avatar {
    border-radius: 50%;
    margin: 0 6px;
  }

  .organization.avatar {
    border-radius: 15%;
  }

  .organization.name {
    white-space: nowrap;
  }

  .organization.contributions {
    margin: 0 8px;
    flex-wrap: wrap;
  }

  .contribution.organization {
    display: flex;
    border: 1px solid #959da5;
    border-radius: 6px;
    padding: 2px 6px;
    padding-left: 0;
    margin: 2px;
    font-size: 12px;
    background-color: #959da520;
  }

  .contribution.organization .avatar {
    margin: 0 4px;
  }

/* Commit calendar */
  .calendar.field {
    margin: 4px 0;
    margin-left: 7px;
  }
  .calendar .day {
    outline: 1px solid rgba(27,31,35,.04);
    outline-offset: -1px;
  }

/* Progress bars */
  svg.bar {
    margin: 4px 0;
  }

/* Language */
  .field.language {
    margin: 0 8px;
    flex-grow: 0;
  }

  .field.language.details {
    display: flex;
    justify-content: space-between;
  }

  .field.language.details small {
    display: flex;
    justify-content: space-between;
    color: #666666;
    text-align: right;
  }

  .field.language.details &gt; *, .field.language.details small &gt; * {
    flex: 1 1 0;
  }
  .field.language.details small &gt; *:not(:last-child) {
    margin-right: 6px;
  }

/* Follow-up */
  .followup.legend {
    font-size: 12px;
  }
  .followup.legend svg {
    margin: 0 3px;
    width: 14px;
    height: 14px;
  }
  .followup.legend svg:first-child {
    margin-left: 0;
  }
  .followup.legend svg:last-child {
    margin-right: 0;
  }

/* Labels */
  .label {
    background-color: #58A6FF30;
    color: #0366D6;
    padding: 0 10px;
    font-weight: 500;
    line-height: 22px;
    margin: 2px 5px;
    white-space: nowrap;
    border-radius: 32px;
    font-size: 12px;
  }

/* Habits */
  .habits {
    margin: 0;
    list-style-type: none;
    padding-left: 37px;
  }

/* Footer */
  footer {
    margin-top: 8px;
    font-size: 10px;
    font-style: italic;
    color: #666666;
    text-align: right;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    padding: 0 4px;
  }

/* Speed test categories */
  .categories {
    display: flex;
    align-items: center;
    justify-content: space-around;
    margin-top: 4px;
  }
  .category {
    display: flex;
    flex-direction: column;
    align-items: center;
    flex: 1 1 0;
  }

/* Gauges */
  .gauge {
    stroke-linecap: round;
    fill: none;
  }
  .gauge.high {
    color: #18b663;
  }
  .gauge.average {
    color: #fb8c00;
  }
  .gauge.low {
    color: #e53935;
  }
  .gauge.info {
    color: #58A6FF;
  }
  .gauge-base, .gauge-arc {
    stroke: currentColor;
    stroke-width: 10;
  }
  .gauge-base {
    stroke-opacity: .2;
  }
  .gauge-arc {
    fill: none;
    stroke-dashoffset: 0;
    animation-delay: 250ms;
    animation: animation-gauge 1s ease forwards
  }
  .gauge text {
    fill: currentColor;
    font-size: 40px;
    font-family: monospace;
    text-anchor: middle;
    font-weight: 600;
  }
  .gauge .title {
    font-size: 18px;
    color: #777777;
  }
  @keyframes animation-gauge {
    from {
      stroke-dasharray: 0 329;
    }
  }
  .audits {
    margin-top: 8px;
  }
  .audit.text {
    min-width: 42px;
  }
  .audit svg {
    margin: 0;
  }
  .audit.high {
    fill: #18b663;
  }
  .audit.average {
    fill: #fb8c00;
  }
  .audit.low {
    fill: #e53935;
  }

  .screenshot {
    width: 452px;
    height: 315px;
    margin: 8px 14px 4px;
    border-radius: 5px;
  }

  svg.large .audits {
    display: inline-flex;
    width: 474px;
  }
  svg.large .audits section:last-child &gt; .field {
    justify-content: right;
  }
  svg.large .screenshot {
    width: 904px;
    height: 630px;
  }

/* Music plugin */
  .tracklist {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-left: 28px;
    margin-top: 4px;
    width: 100%;
  }
  .track {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 4px;
  }
  .track img {
    margin: 0 10px;
    border-radius: 7px;
    flex-shrink: 0;
  }
  .track .name {
    font-size: 14px;
    line-height: 14px;
    font-weight: 600;
  }
  .track .artist, .track .played-at {
    font-size: 12px;
    color: #666666;
  }
  .track .infos {
    flex-grow: 1;
  }
  svg.large .tracklist {
    flex-direction: row;
    flex-wrap: wrap;
  }
  svg.large .track {
    width: 25%;
  }

/* Posts plugin */
  .post {
    align-items: flex-start;
  }
  .post .infos {
    display: flex;
    margin-bottom: 4px;
  }
  .post .infos .left {
    flex-shrink: 0;
    font-size: 12px;
    color: #666666;
    width: 72px;
    padding-top: 1px;
    text-align: center;
  }
  .post .infos .cover {
    width: 100%;
    height: 56px;
    background-position: center;
    background-size: cover;
    border-radius: 6px;
    overflow: hidden;
  }
  .post .infos .right {
    width: 376px;
    padding-left: 4px;
  }
  .post .infos .title, .post .infos .description {
    font-size: 14px;
    white-space: normal;
    overflow: hidden;
    text-overflow: ellipsis;
    max-height: 38px;
    /* May not work in all browsers */
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }
  .post .infos .description {
    margin-top: 3px;
    font-size: 12px;
    max-height: 48px;
    color: #666666;
    -webkit-line-clamp: 3;
  }

/* Topics */
  .topics {
    display: flex;
    flex-wrap: wrap;
  }

  .topics img {
    border-radius: 5px;
    margin: 4px;
  }

/* Tweets */
  .tweet {
    font-size: 13px;
    margin-top: 6px;
    margin-bottom: 16px;
    margin-left: 18px;
    border-left: 3px solid #777777B2;
    padding-left: 6px;
  }

  .tweet .mention, .tweet .link, .tweet .hashtag {
    color: #0366d6;
  }

  .tweet .date {
    margin: 6px 0;
    font-size: 12px;
    color: #666666;
  }

  .tweet .attachments {
    display: flex;
    width: 450px;
    margin-top: 8px;
  }

  .tweet .attachments &gt; div {
    flex: 1 1 0;
    width: 0;
    border-radius: 6px;
    background-position: center;
    background-size: cover;
    height: 200px;
    margin: 2px;
    box-shadow: 0px 0px 1px #777777A0;
    overflow: hidden;
    display: flex;
    align-items: flex-end;
  }

  .tweet .attachments .infos {
    background-color: #000000D0;
    color: white;
    display: flex;
    flex-direction: column;
    width: 100%;
    padding-bottom: 4px;
  }

  .tweet .attachments .infos &gt; div {
    margin: 4px 8px 0;
  }

  .tweet .attachments .infos .title {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }

  .tweet .attachments .infos .description {
    font-size: 11px;
    color: #666666;
  }

/* Charts and graphs */
  .chart {
    padding: 0 8px;
  }

  .chart-bars {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    width: 100%;
    margin: 8px 0 4px;
    flex-grow: 1;
    min-height: 70px;
  }

  .chart-bars .entry {
    flex: 1 1 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 10px;
    color: #666666;
  }

  .chart-bars .entry .value {
    font-size: 7px;
  }

  .chart-bars .entry .empty {
    width: 100%;
    text-align: center;
  }

  .chart-bars .bar {
    width: 7px;
    background-color: var(--color-calendar-graph-day-bg);
    border: 1px solid var(--color-calendar-graph-day-border);
    border-radius: 5px;
  }

  .chart-bars.horizontal {
    flex-direction: column;
    height: 100%;
  }

  .chart-bars.horizontal .entry {
    align-items: center;
    flex-direction: row;
    width: 100%;
    min-height: 1rem;
  }

  .chart-bars.horizontal .entry .name {
    flex-shrink: 0;
    text-align: right;
    width: 34%;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }

  .chart-bars .entry .bottom {
    margin-bottom: -1rem;
    line-height: 1rem;
  }

  .chart-bars.horizontal .bar {
    height: 7px;
    width: auto;
    margin: 0 6px;
  }

/* Repository */
  .repository {
    display: flex;
    flex-direction: column;
    width: 100%;
    margin: 6px 0;
  }

  .repository .name {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 440px;
  }

  .repository .name span:first-child {
    color: #58a6ff;
  }

  .repository .name span:last-child {
    color: #666666;
    font-size: 10px;
  }

  .repository .description {
    display: block;
    width: 440px;
    white-space: normal;
  }

  .repository .description, .repository .infos {
    color: #666666;
    margin-left: 38px;
    font-size: 13px;
  }

  .repository .infos &gt; div {
    display: flex;
    align-items: center;
    margin-right: 16px;
  }

  .repository .infos svg {
    margin: 0;
    margin-right: 4px;
  }

/* Activity */
  .activity {
    margin-bottom: 12px;
  }

  .activity .field {
    width: 100%;
    overflow: hidden;
    text-overflow: ellipsis;
    max-width: 450px;
    white-space: nowrap;
    margin-bottom: 0;
  }

  .activity .field .content {
    flex-grow: 1;
    text-overflow: ellipsis;
    overflow: hidden;
  }

  .activity .repo, .activity .issue, .activity .commit .sha {
    display: inline;
    color: #58a6ff;
  }

  .activity .code {
    background-color: #7777771F;
    padding: 1px 5px;
    font-size: 80%;
    border-radius: 6px;
    color: #777777;
    font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,monospace;
    margin: 0 4px -3px;
  }

  .activity .bold, .activity .user {
    font-weight: 600;
  }

  .activity .details, .activity .timestamp {
    padding-left: 38px;
    display: flex;
    flex-direction: column;
    font-size: 13px;
    color: #666666;
  }

  .activity .timestamp {
    font-size: 10px;
    margin-top: 4px;
  }

  .activity .commit .sha {
    font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,monospace;
  }

  .activity .commit .message {
    overflow: hidden;
    text-overflow: ellipsis;
    width: 360px;
    white-space: nowrap;
  }

  .activity .details &gt; .comment {
    overflow: hidden;
    text-overflow: ellipsis;
    display: block;
    width: 420px;
    margin-top: 6px;
    border-left: 3px solid #777777B2;
    padding-left: 6px;
    /* May not work in all browsers */
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }

  svg.large .activity .field {
    max-width: 900px;
  }

/* People */
  .people {
    padding: 0 10px;
  }

  .people .avatar {
    margin: 0 2px;
  }

/* Projects */
  .project .description {
    overflow: hidden;
    text-overflow: ellipsis;
    display: block;
    width: 420px;
    margin-left: 37px;
    max-height: 38px;
    font-size: 12px;
    white-space: normal;
    /* May not work in all browsers */
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }

/* Anilist */
  .anilist {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-left: 28px;
    margin-top: 4px;
  }

  .anilist .media {
    display: flex;
    margin-bottom: 4px;
    width: 450px;
  }
  .anilist .media img {
    margin: 0 10px;
    border-radius: 7px;
  }

  .anilist .media .about {
    flex-grow: 1;
  }
  .anilist .media .name {
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-size: 14px;
    line-height: 14px;
    color: #58a6ff;
  }
  .anilist .media .infos {
    font-size: 12px;
    color: #666666;
  }
  .anilist .media .infos &gt; div {
    display: inline-flex;
    align-items: center;
    margin-right: 16px;
  }
  .anilist .media .infos svg {
    fill: currentColor;
    height: 12px;
    width: 12px;
    margin: 0;
    margin-right: 4px;
  }

  .anilist .media .description {
    overflow: hidden;
    text-overflow: ellipsis;
    display: block;
    width: 380px;
    max-height: 38px;
    font-size: 12px;
    white-space: normal;
    /* May not work in all browsers */
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }

  .anilist .characters {
    display: flex;
    flex-wrap: wrap;
  }

  .anilist .characters img {
    margin: 2px;
    border-radius: 7px;
  }

/* Licenses */
  .licenses {
    display: flex;
  }
  .licenses .column {
    align-items: flex-start;
    font-size: 12px;
    color: #666666;
    flex-shrink: 0;
  }
  .licenses-details {
    margin-top: 8px;
  }
  .field.license.details {
    display: flex;
    justify-content: space-between;
  }
  .field.license.details small {
    display: flex;
    justify-content: space-between;
    color: #666666;
    text-align: right;
  }
  .licenses .column:nth-child(1) {
    margin-left: 13px;
    width: 25%;
  }
  .licenses .column:nth-child(2) {
    width: 25%;
  }
  .licenses .column:nth-child(3) {
    width: 50%;
  }
  .licenses .column svg {
    height: 12px;
    width: 12px;
  }
  .licenses .column .title {
    font-weight: 600;
    margin-left: 15px;
  }
  .licenses .column .permission svg {
    fill: #56d364;
  }
  .licenses .column .limitation svg {
    fill: #f85149;
  }
  .licenses .column .condition svg {
    fill: #58a6ff;
  }

/* Contributors */
  .contributors {
    display: flex;
    flex-wrap: wrap;
    margin-left: 6px;
  }
  .contributors .label {
    padding-left: 0;
    display: flex;
    align-items: center;
  }
  .contributors .label img {
    margin-left: 0;
  }
  .contributors .contributions {
    display: flex;
    align-items: center;
    font-size: .7rem;
    margin-left: 6px;
    margin-right: -10px;
    background-color: #58A6FF10;
    padding: 0 7px;
    border-top-right-radius: 32px;
    border-bottom-right-radius: 32px;
  }
  .contributors .contributions svg {
    fill: #0366D6;
    margin-left: 4px;
    width: .8rem;
    height: .8rem;
  }

/* Introduction */
  .introduction {
    white-space: normal;
    margin: 0 13px 2px;
  }

/* Stackoverflow */
  .stackoverflow {
    margin-left: 38px;
  }
  .stackoverflow .entry {
    margin: 4px 0 12px;
  }
  .stackoverflow .title {
    color: #58a6ff;
    white-space: normal;
    align-items: flex-start;
  }
  .stackoverflow .body, .stackoverflow .infos {
    color: #666666;
    font-size: 13px;
    margin-left: 32px;
  }
  .stackoverflow .infos {
    display: flex;
    align-items: center;
  }
  .stackoverflow .infos &gt; div {
    display: inline-flex;
    align-items: center;
    margin-right: 16px;
  }
  .stackoverflow .infos svg {
    fill: currentColor;
    height: 12px;
    width: 12px;
    margin: 0;
    margin-right: 4px;
    flex-shrink: 0;
  }
  .stackoverflow .body {
    overflow: hidden;
    text-overflow: ellipsis;
    border-left: 3px solid #777777B2;
    padding-left: 6px;
    width: 400px;
  }

/* Achievements */
  .achievement {
    display: flex;
    margin: 4px 0;
  }
  .achievement .icon {
    margin: 0 4px;
    width: 44px;
    height: 44px;
  }
  .achievement .text {
    font-size: 12px;
    color: #666666;
  }
  .achievement .unlock {
    font-size: 9px;
    color: #666666;
  }
  .achievement .title {
    font-size: 14px;
    color: #58A6FF;
  }
  .achievement .gauge.info {
    color: #58A6FF;
  }
  .achievement.x .title {
    color: #666666;
  }
  .achievement.x .gauge.info {
    color: #B0B0B0;
  }
  .achievement.b .title {
    color: #9D8FFF;
  }
  .achievement.b .gauge.info {
    color: #9E91FF;
  }
  .achievement.a .title {
    color: #D79533;
  }
  .achievement.a .gauge.info {
    color: #E7BD69;
  }
  .achievement.s .title {
    color: #FF0000;
  }
  .achievement.s .gauge.info {
    color: #FF0000;
  }
  .achievement.s .icon {
    filter: sepia() saturate(100);
  }
  .achievement.secret .title{
    color: #FF76CD;
  }
  .achievement.secret .gauge.info {
    color: #FF79D1;
  }
  .achievement .gh {
    border: 1px solid currentColor;
    border-radius: 16px;
    font-size: 10px;
    padding: 0 5px;
  }
  .achievement .gauge-base, .achievement .gauge-arc {
    stroke-width: 6;
  }

/* RSS feed */
  .rss {
    align-items: flex-start;
  }
  .rss .infos {
    margin-bottom: 3px;
  }
  .rss .infos .date {
    font-size: 10px;
    color: #666666;
  }

/* Skyline */
  .skyline-animation {
    margin: 2px 13px 6px;
    border-radius: 10px;
    background-color: #030D21;
    overflow: hidden;
  }

/* Markdown and syntax highlighting */
  .markdown b, .markdown i {
    display: inline-block;
    width: 97%;
  }
  code {
    background-color: #7777771F;
    display: inline-block;
    border-radius: 6px;
    color: #777777;
    padding: 1px 5px;
    font-size: 80%;
    font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,monospace;
  }
  code[class^=language-] {
    white-space: pre-wrap;
    width: 97%;
    margin-top: 4px;
  }
  .token.comment {
    color: #669900;
  }
  .token.punctuation {
    color: #8a93a8;
  }
  .token.namespace, .token.constant, .token.symbol, .token.keyword {
    color: #b44418;
  }
  .token.regex, .token.string, .token.char, .token.number, .token.boolean {
    color: #2777AA;
  }
  .token.property, .token.tag {
    color: #48428a;
  }
  .token.builtin, .token.operator {
    color: #106cbc;
  }
  .token.trimmed {
    font-style: italic;
    color: #77777760
  }

/* Charts */
  .ct-line {
    stroke-width: 2px !important;
    stroke: #58A6FF !important;
  }
  .ct-area {
    fill: #58A6FF !important;
  }
  .ct-label {
    fill: rgba(127, 127, 127, 0.8) !important;
    color: rgba(127, 127, 127, 0.8) !important;
  }
  .ct-grid {
    stroke: rgba(127, 127, 127, 0.4) !important;
  }

/* Autosize */
  .autosize {
    width: auto;
    height: auto;
  }

/* Fade animation */
  .af {
    opacity: 0;
    animation: animation-fade 1s ease forwards;
  }
  @keyframes animation-fade {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }

/* Twemoji and GitHub emoji */
  .twemoji, .gemoji {
    height: 1em;
    width: 1em;
    margin-bottom: -.125em;
  }

/* Cake day */
  .cakeday, .cakeday svg {
    animation: animation-rainbow 1.2s;
    animation-iteration-count: infinite;
    animation-timing-function: steps(1);
  }

/* Rainbow animation */
  @keyframes animation-rainbow {
    0%, 100%{ color: #7F00FF; fill: #7F00FF; }
    14% { color: #A933FF; fill: #A933FF; }
    29%{ color: #007FFF; fill: #007FFF; }
    43%{ color: #00FF7F; fill: #00FF7F; }
		57%{ color: #FFFF00; fill: #FFFF00; }
		71%{ color: #FF7F00; fill: #FF7F00; }
		86%{ color: #FF0000; fill: #FF0000; }
  }

/* Calendar */
  :root {
    --color-calendar-graph-day-bg: #ebedf0;
    --color-calendar-graph-day-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L1-bg: #9be9a8;
    --color-calendar-graph-day-L2-bg: #40c463;
    --color-calendar-graph-day-L3-bg: #30a14e;
    --color-calendar-graph-day-L4-bg: #216e39;
    --color-calendar-halloween-graph-day-L1-bg: #ffee4a;
    --color-calendar-halloween-graph-day-L2-bg: #ffc501;
    --color-calendar-halloween-graph-day-L3-bg: #fe9600;
    --color-calendar-halloween-graph-day-L4-bg: #03001c;
    --color-calendar-graph-day-L4-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L3-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L2-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L1-border: rgba(27,31,35,0.06);
  }

/* End delimiter */
  #metrics-end {
    width: 100%;
  }

  .no-animations * {
    transition-delay: 0s !important;
    transition-duration: 0s !important;
    animation-delay: -0.0001s !important;
    animation-duration: 0s !important;
    animation-play-state: paused !important;
    caret-color: transparent !important;
  }</style>
    <foreignObject x="0" y="0" width="100%" height="100%">
        <div xmlns="http://www.w3.org/1999/xhtml" xmlns:xlink="http://www.w3.org/1999/xlink">
            <section>
                <h1 class="field">
                    <img class="avatar" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAaQAAAGkCAYAAAB+TFE1AAAGA0lEQVR4Ae3BwW3UAAAEwGV1f1fi+lzD1edGchXAGyWfgBCbaGZ+vL29/QwA/GcNAAxoAGBAAwADGgAY0ADAgAYABjQAMKABgAENAAxoAGBAAwADGgAY0ADAgAYABjQAMKABgAENAAxoAGBAAwADGgAY0ADAgAYABjQAMKABgAENAAxoAGBAAwADGgAY0ADAgAYABjQAMKABgAENAAxoAGDAI0Pu1zPwGedxhd/dr2fgM87jyoIGAAY0ADCgAYABDQAMaABgQAMAAxoAGNAAwIAGAAY0ADCgAYABDQAMaABgQAMAAxoAGNAAwIAGAAY0ADCgAYABDQAMaABgQAMAAxoAGNAAwIAGAAY0ADCgAYABDQAMaABgQAMAAxoAGNAAwIAGAAY0ADCgAYABDQAMaABgQAMAAxoAGNAAwIAGAAY0ADCgAYABDQAMaABgQAMAAxoAGNAAwIAGAAY0ADCgAYABDQAMaABgQAMAAxoAGNAAwIAGAAY0ADCgAYABDQAMaABgQAMAAxoAGNAAwIAGAAY0ADCgAYABDQAMaABgwCPwhd2vZ4Dv4ZEh53GF9+7XM8DfO48r7GoAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGPMK887jCe/frGT52Hlfgq2kAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGPAJf1HlcAb6PBgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADHhkyP16ho+dxxXgz92vZ/jYeVxZ0ADAgAYABjQAMKABgAENAAxoAGBAAwADGgAY0ADAgAYABjQAMKABgAENAAxoAGBAAwADGgAY0ADAgAYABjQAMKABgAENAAxoAGBAAwADGgAY0ADAgAYABjQAMKABgAENAAxoAGBAAwADGgAY0ADAgAYABjQAMKABgAENAAxoAGBAAwADGgAY0ADAgAYABjQAMKABgAENAAxoAGBAAwADGgAY0ADAgAYABjQAMKABgAENAAxoAGBAAwADGgAY0ADAgAYABjQAMKABgAENAAxoAGBAAwADGgAY0ADAgAYABjQAMKABgAENAAxoAGDAI0PO4wrAv3AeV9jWAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCABgAGNAAwoAGAAQ0ADGgAYEADAAMaABjQAMCAX0wQHvEhz/x8AAAAAElFTkSuQmCC" width="20" height="20" />
                    <span>Sebastian Tyda</span>
                </h1>
                <div class="row">
                    <section>
                        <div class="field ">
            
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0zM8 0a8 8 0 100 16A8 8 0 008 0zm.5 4.75a.75.75 0 00-1.5 0v3.5a.75.75 0 00.471.696l2.5 1a.75.75 0 00.557-1.392L8.5 7.742V4.75z"/></svg>
              Joined GitHub 1 year ago
            
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M5.5 3.5a2 2 0 100 4 2 2 0 000-4zM2 5.5a3.5 3.5 0 115.898 2.549 5.507 5.507 0 013.034 4.084.75.75 0 11-1.482.235 4.001 4.001 0 00-7.9 0 .75.75 0 01-1.482-.236A5.507 5.507 0 013.102 8.05 3.49 3.49 0 012 5.5zM11 4a.75.75 0 100 1.5 1.5 1.5 0 01.666 2.844.75.75 0 00-.416.672v.352a.75.75 0 00.574.73c1.2.289 2.162 1.2 2.522 2.372a.75.75 0 101.434-.44 5.01 5.01 0 00-2.56-3.012A3 3 0 0011 4z"/></svg>
            Followed by 17 users
          </div>
                        <div class="field hire">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M6.75 0A1.75 1.75 0 005 1.75V3H1.75A1.75 1.75 0 000 4.75v8.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3H11V1.75A1.75 1.75 0 009.25 0h-2.5zM9.5 3V1.75a.25.25 0 00-.25-.25h-2.5a.25.25 0 00-.25.25V3h3zM5 4.5H1.75a.25.25 0 00-.25.25V6a2 2 0 002 2h9a2 2 0 002-2V4.75a.25.25 0 00-.25-.25H5zm-1.5 5a3.484 3.484 0 01-2-.627v4.377c0 .138.112.25.25.25h12.5a.25.25 0 00.25-.25V8.873a3.484 3.484 0 01-2 .627h-9z"/></svg>
              Available for hire!
            </div>
                    </section>
                    <section>
                        <div class="field calendar">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 210 11" width="210" height="16">
                                <g>
                                    <rect class="day" x="0" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
                                    <rect class="day" x="15" y="0" width="11" height="11" fill="#9be9a8" rx="2" ry="2"/>
                                    <rect class="day" x="30" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
                                    <rect class="day" x="45" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
                                    <rect class="day" x="60" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
                                    <rect class="day" x="75" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
                                    <rect class="day" x="90" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
                                    <rect class="day" x="105" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
                                    <rect class="day" x="120" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
                                    <rect class="day" x="135" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
                                    <rect class="day" x="150" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
                                    <rect class="day" x="165" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
                                    <rect class="day" x="180" y="0" width="11" height="11" fill="#216e39" rx="2" ry="2"/>
                                    <rect class="day" x="195" y="0" width="11" height="11" fill="#ebedf0" rx="2" ry="2"/>
                                </g>
                            </svg>
                        </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1 2.5A2.5 2.5 0 013.5 0h8.75a.75.75 0 01.75.75v3.5a.75.75 0 01-1.5 0V1.5h-8a1 1 0 00-1 1v6.708A2.492 2.492 0 013.5 9h3.25a.75.75 0 010 1.5H3.5a1 1 0 100 2h5.75a.75.75 0 010 1.5H3.5A2.5 2.5 0 011 11.5v-9zm13.23 7.79a.75.75 0 001.06-1.06l-2.505-2.505a.75.75 0 00-1.06 0L9.22 9.229a.75.75 0 001.06 1.061l1.225-1.224v6.184a.75.75 0 001.5 0V9.066l1.224 1.224z"/></svg>
            Contributed to 16 repositories
          </div>
                    </section>
                </div>
            </section>
            <section class="largeable largeable-inline-flex">
                <div class="row">
                    <section>
                        <h2 class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.5 1.75a.75.75 0 00-1.5 0v12.5c0 .414.336.75.75.75h14.5a.75.75 0 000-1.5H1.5V1.75zm14.28 2.53a.75.75 0 00-1.06-1.06L10 7.94 7.53 5.47a.75.75 0 00-1.06 0L3.22 8.72a.75.75 0 001.06 1.06L7 7.06l2.47 2.47a.75.75 0 001.06 0l5.25-5.25z"/></svg>
            Activity
          </h2>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M10.5 7.75a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0zm1.43.75a4.002 4.002 0 01-7.86 0H.75a.75.75 0 110-1.5h3.32a4.001 4.001 0 017.86 0h3.32a.75.75 0 110 1.5h-3.32z"/></svg>
            319 Commits
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2.5 1.75a.25.25 0 01.25-.25h8.5a.25.25 0 01.25.25v7.736a.75.75 0 101.5 0V1.75A1.75 1.75 0 0011.25 0h-8.5A1.75 1.75 0 001 1.75v11.5c0 .966.784 1.75 1.75 1.75h3.17a.75.75 0 000-1.5H2.75a.25.25 0 01-.25-.25V1.75zM4.75 4a.75.75 0 000 1.5h4.5a.75.75 0 000-1.5h-4.5zM4 7.75A.75.75 0 014.75 7h2a.75.75 0 010 1.5h-2A.75.75 0 014 7.75zm11.774 3.537a.75.75 0 00-1.048-1.074L10.7 14.145 9.281 12.72a.75.75 0 00-1.062 1.058l1.943 1.95a.75.75 0 001.055.008l4.557-4.45z"/></svg>
            1 Pull request reviewed
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M7.177 3.073L9.573.677A.25.25 0 0110 .854v4.792a.25.25 0 01-.427.177L7.177 3.427a.25.25 0 010-.354zM3.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122v5.256a2.251 2.251 0 11-1.5 0V5.372A2.25 2.25 0 011.5 3.25zM11 2.5h-1V4h1a1 1 0 011 1v5.628a2.251 2.251 0 101.5 0V5A2.5 2.5 0 0011 2.5zm1 10.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.75 12a.75.75 0 100 1.5.75.75 0 000-1.5z"/></svg>
            0 Pull requests opened
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8 1.5a6.5 6.5 0 100 13 6.5 6.5 0 000-13zM0 8a8 8 0 1116 0A8 8 0 010 8zm9 3a1 1 0 11-2 0 1 1 0 012 0zm-.25-6.25a.75.75 0 00-1.5 0v3.5a.75.75 0 001.5 0v-3.5z"/></svg>
            0 Issues opened
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2.75 2.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h2a.75.75 0 01.75.75v2.19l2.72-2.72a.75.75 0 01.53-.22h4.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25H2.75zM1 2.75C1 1.784 1.784 1 2.75 1h10.5c.966 0 1.75.784 1.75 1.75v7.5A1.75 1.75 0 0113.25 12H9.06l-2.573 2.573A1.457 1.457 0 014 13.543V12H2.75A1.75 1.75 0 011 10.25v-7.5z"/></svg>
            8 issue comments
          </div>
                    </section>
                    <section>
                        <h2 class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.326 1.973a1.2 1.2 0 011.49-.832c.387.112.977.307 1.575.602.586.291 1.243.71 1.7 1.296.022.027.042.056.061.084A13.22 13.22 0 018 3c.67 0 1.289.037 1.861.108l.051-.07c.457-.586 1.114-1.004 1.7-1.295a9.654 9.654 0 011.576-.602 1.2 1.2 0 011.49.832c.14.493.356 1.347.479 2.29.079.604.123 1.28.07 1.936.541.977.773 2.11.773 3.301C16 13 14.5 15 8 15s-8-2-8-5.5c0-1.034.238-2.128.795-3.117-.08-.712-.034-1.46.052-2.12.122-.943.34-1.797.479-2.29zM8 13.065c6 0 6.5-2 6-4.27C13.363 5.905 11.25 5 8 5s-5.363.904-6 3.796c-.5 2.27 0 4.27 6 4.27z"/><path d="M4 8a1 1 0 012 0v1a1 1 0 01-2 0V8zm2.078 2.492c-.083-.264.146-.492.422-.492h3c.276 0 .505.228.422.492C9.67 11.304 8.834 12 8 12c-.834 0-1.669-.696-1.922-1.508zM10 8a1 1 0 112 0v1a1 1 0 11-2 0V8z"/></svg>              Community stats
          </h2>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.5 14.25c0 .138.112.25.25.25H4v-1.25a.75.75 0 01.75-.75h2.5a.75.75 0 01.75.75v1.25h2.25a.25.25 0 00.25-.25V1.75a.25.25 0 00-.25-.25h-8.5a.25.25 0 00-.25.25v12.5zM1.75 16A1.75 1.75 0 010 14.25V1.75C0 .784.784 0 1.75 0h8.5C11.216 0 12 .784 12 1.75v12.5c0 .085-.006.168-.018.25h2.268a.25.25 0 00.25-.25V8.285a.25.25 0 00-.111-.208l-1.055-.703a.75.75 0 11.832-1.248l1.055.703c.487.325.779.871.779 1.456v5.965A1.75 1.75 0 0114.25 16h-3.5a.75.75 0 01-.197-.026c-.099.017-.2.026-.303.026h-3a.75.75 0 01-.75-.75V14h-1v1.25a.75.75 0 01-.75.75h-3zM3 3.75A.75.75 0 013.75 3h.5a.75.75 0 010 1.5h-.5A.75.75 0 013 3.75zM3.75 6a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h-.5zM3 9.75A.75.75 0 013.75 9h.5a.75.75 0 010 1.5h-.5A.75.75 0 013 9.75zM7.75 9a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h-.5zM7 6.75A.75.75 0 017.75 6h.5a.75.75 0 010 1.5h-.5A.75.75 0 017 6.75zM7.75 3a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h-.5z"/></svg>
            Member of 1 organization
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M5.5 3.5a2 2 0 100 4 2 2 0 000-4zM2 5.5a3.5 3.5 0 115.898 2.549 5.507 5.507 0 013.034 4.084.75.75 0 11-1.482.235 4.001 4.001 0 00-7.9 0 .75.75 0 01-1.482-.236A5.507 5.507 0 013.102 8.05 3.49 3.49 0 012 5.5zM11 4a.75.75 0 100 1.5 1.5 1.5 0 01.666 2.844.75.75 0 00-.416.672v.352a.75.75 0 00.574.73c1.2.289 2.162 1.2 2.522 2.372a.75.75 0 101.434-.44 5.01 5.01 0 00-2.56-3.012A3 3 0 0011 4z"/></svg>
            Following 30 users
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M4.25 2.5c-1.336 0-2.75 1.164-2.75 3 0 2.15 1.58 4.144 3.365 5.682A20.565 20.565 0 008 13.393a20.561 20.561 0 003.135-2.211C12.92 9.644 14.5 7.65 14.5 5.5c0-1.836-1.414-3-2.75-3-1.373 0-2.609.986-3.029 2.456a.75.75 0 01-1.442 0C6.859 3.486 5.623 2.5 4.25 2.5zM8 14.25l-.345.666-.002-.001-.006-.003-.018-.01a7.643 7.643 0 01-.31-.17 22.075 22.075 0 01-3.434-2.414C2.045 10.731 0 8.35 0 5.5 0 2.836 2.086 1 4.25 1 5.797 1 7.153 1.802 8 3.02 8.847 1.802 10.203 1 11.75 1 13.914 1 16 2.836 16 5.5c0 2.85-2.045 5.231-3.885 6.818a22.08 22.08 0 01-3.744 2.584l-.018.01-.006.003h-.002L8 14.25zm0 0l.345.666a.752.752 0 01-.69 0L8 14.25z"/></svg>
            Sponsoring 0 repositories
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"/></svg>
            Starred 48 repositories
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"/></svg>
            Watching 15 repositories
          </div>
                    </section>
                </div>
            </section>
            <section class="largeable largeable-inline-flex">
                <div class="row">
                    <section>
                        <h2 class="field">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h8.75a.75.75 0 01.75.75v12.5a.75.75 0 01-.75.75h-2.5a.75.75 0 110-1.5h1.75v-2h-8a1 1 0 00-.714 1.7.75.75 0 01-1.072 1.05A2.495 2.495 0 012 11.5v-9zm10.5-1V9h-8c-.356 0-.694.074-1 .208V2.5a1 1 0 011-1h8zM5 12.25v3.25a.25.25 0 00.4.2l1.45-1.087a.25.25 0 01.3 0L8.6 15.7a.25.25 0 00.4-.2v-3.25a.25.25 0 00-.25-.25h-3.5a.25.25 0 00-.25.25z"/></svg>
          14 Repositories 
        </h2>
                        <div class="row">
                            <section>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8.75.75a.75.75 0 00-1.5 0V2h-.984c-.305 0-.604.08-.869.23l-1.288.737A.25.25 0 013.984 3H1.75a.75.75 0 000 1.5h.428L.066 9.192a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.514 3.514 0 00.686.45A4.492 4.492 0 003 11c.88 0 1.556-.22 2.023-.454a3.515 3.515 0 00.686-.45l.045-.04.016-.015.006-.006.002-.002.001-.002L5.25 9.5l.53.53a.75.75 0 00.154-.838L3.822 4.5h.162c.305 0 .604-.08.869-.23l1.289-.737a.25.25 0 01.124-.033h.984V13h-2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-2.5V3.5h.984a.25.25 0 01.124.033l1.29.736c.264.152.563.231.868.231h.162l-2.112 4.692a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.517 3.517 0 00.686.45A4.492 4.492 0 0013 11c.88 0 1.556-.22 2.023-.454a3.512 3.512 0 00.686-.45l.045-.04.01-.01.006-.005.006-.006.002-.002.001-.002-.529-.531.53.53a.75.75 0 00.154-.838L13.823 4.5h.427a.75.75 0 000-1.5h-2.234a.25.25 0 01-.124-.033l-1.29-.736A1.75 1.75 0 009.735 2H8.75V.75zM1.695 9.227c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L3 6.327l-1.305 2.9zm10 0c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L13 6.327l-1.305 2.9z"/></svg>
              
                Prefers WTFPL license
              
            </div>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"/></svg>
              9 Releases
            </div>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8.878.392a1.75 1.75 0 00-1.756 0l-5.25 3.045A1.75 1.75 0 001 4.951v6.098c0 .624.332 1.2.872 1.514l5.25 3.045a1.75 1.75 0 001.756 0l5.25-3.045c.54-.313.872-.89.872-1.514V4.951c0-.624-.332-1.2-.872-1.514L8.878.392zM7.875 1.69a.25.25 0 01.25 0l4.63 2.685L8 7.133 3.245 4.375l4.63-2.685zM2.5 5.677v5.372c0 .09.047.171.125.216l4.625 2.683V8.432L2.5 5.677zm6.25 8.271l4.625-2.683a.25.25 0 00.125-.216V5.677L8.75 8.432v5.516z"/></svg>
              0 Packages
            </div>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" d="M2.5 3.5c0-.133.058-.318.282-.55.227-.237.592-.484 1.1-.708C4.899 1.795 6.354 1.5 8 1.5c1.647 0 3.102.295 4.117.742.51.224.874.47 1.101.707.224.233.282.418.282.551 0 .133-.058.318-.282.55-.227.237-.592.484-1.1.708C11.101 5.205 9.646 5.5 8 5.5c-1.647 0-3.102-.295-4.117-.742-.51-.224-.874-.47-1.101-.707-.224-.233-.282-.418-.282-.551zM1 3.5c0-.626.292-1.165.7-1.59.406-.422.956-.767 1.579-1.041C4.525.32 6.195 0 8 0c1.805 0 3.475.32 4.722.869.622.274 1.172.62 1.578 1.04.408.426.7.965.7 1.591v9c0 .626-.292 1.165-.7 1.59-.406.422-.956.767-1.579 1.041C11.476 15.68 9.806 16 8 16c-1.805 0-3.475-.32-4.721-.869-.623-.274-1.173-.62-1.579-1.04-.408-.426-.7-.965-.7-1.591v-9zM2.5 8V5.724c.241.15.503.286.779.407C4.525 6.68 6.195 7 8 7c1.805 0 3.475-.32 4.722-.869.275-.121.537-.257.778-.407V8c0 .133-.058.318-.282.55-.227.237-.592.484-1.1.708C11.101 9.705 9.646 10 8 10c-1.647 0-3.102-.295-4.117-.742-.51-.224-.874-.47-1.101-.707C2.558 8.318 2.5 8.133 2.5 8zm0 2.225V12.5c0 .133.058.318.282.55.227.237.592.484 1.1.708 1.016.447 2.471.742 4.118.742 1.647 0 3.102-.295 4.117-.742.51-.224.874-.47 1.101-.707.224-.233.282-.418.282-.551v-2.275c-.241.15-.503.285-.778.406-1.247.549-2.917.869-4.722.869-1.805 0-3.475-.32-4.721-.869a6.236 6.236 0 01-.779-.406z"/></svg>
              47.8 MB used
            </div>
                                <div class="field ">
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M2.75 1.5a.25.25 0 00-.25.25v12.5c0 .138.112.25.25.25h10.5a.25.25 0 00.25-.25V4.664a.25.25 0 00-.073-.177l-2.914-2.914a.25.25 0 00-.177-.073H2.75zM1 1.75C1 .784 1.784 0 2.75 0h7.586c.464 0 .909.184 1.237.513l2.914 2.914c.329.328.513.773.513 1.237v9.586A1.75 1.75 0 0113.25 16H2.75A1.75 1.75 0 011 14.25V1.75zm7 1.5a.75.75 0 01.75.75v1.5h1.5a.75.75 0 010 1.5h-1.5v1.5a.75.75 0 01-1.5 0V7h-1.5a.75.75 0 010-1.5h1.5V4A.75.75 0 018 3.25zm-3 8a.75.75 0 01.75-.75h4.5a.75.75 0 010 1.5h-4.5a.75.75 0 01-.75-.75z"/></svg>
                  
                    96.5k added, 28k removed
                  
                </div>
                            </section>
                            <section>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M4.25 2.5c-1.336 0-2.75 1.164-2.75 3 0 2.15 1.58 4.144 3.365 5.682A20.565 20.565 0 008 13.393a20.561 20.561 0 003.135-2.211C12.92 9.644 14.5 7.65 14.5 5.5c0-1.836-1.414-3-2.75-3-1.373 0-2.609.986-3.029 2.456a.75.75 0 01-1.442 0C6.859 3.486 5.623 2.5 4.25 2.5zM8 14.25l-.345.666-.002-.001-.006-.003-.018-.01a7.643 7.643 0 01-.31-.17 22.075 22.075 0 01-3.434-2.414C2.045 10.731 0 8.35 0 5.5 0 2.836 2.086 1 4.25 1 5.797 1 7.153 1.802 8 3.02 8.847 1.802 10.203 1 11.75 1 13.914 1 16 2.836 16 5.5c0 2.85-2.045 5.231-3.885 6.818a22.08 22.08 0 01-3.744 2.584l-.018.01-.006.003h-.002L8 14.25zm0 0l.345.666a.752.752 0 01-.69 0L8 14.25z"/></svg>
              0 Sponsors
            </div>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"/></svg>
              19 Stargazers
            </div>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"/></svg>
              9 Forkers
            </div>
                                <div class="field">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"/></svg>
              16 Watchers
            </div>
                            </section>
                        </div>
                    </section>
                </div>
            </section>
            <section>
                <h2 class="field">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M6 2a.75.75 0 01.696.471L10 10.731l1.304-3.26A.75.75 0 0112 7h3.25a.75.75 0 010 1.5h-2.742l-1.812 4.528a.75.75 0 01-1.392 0L6 4.77 4.696 8.03A.75.75 0 014 8.5H.75a.75.75 0 010-1.5h2.742l1.812-4.529A.75.75 0 016 2z"/></svg>
      Overall issues and pull requests status
    </h2>
            </section>
            <div class="column largeable">
                <h3>
          On s-tyda's repositories
        </h3>
                <div class="row fill-width">
                    <section class="column">
                        <h3 class="no-margin-top">Issues</h3>
                        <svg class="bar" xmlns="http://www.w3.org/2000/svg" width="220" height="8">
                            <mask id="issues-bar">
                                <rect x="0" y="0" width="220" height="8" fill="white" rx="5"/>
                            </mask>
                            <rect mask="url(#issues-bar)" x="0" y="0" width="220" height="8" fill="#d1d5da"/>
                            <rect mask="url(#issues-bar)" x="0" y="0" width="0" height="8" fill="#28a745"/>
                            <rect mask="url(#issues-bar)" x="0" y="0" width="0" height="8" fill="#d73a49"/>
                        </svg>
                        <div class="followup legend field horizontal fill-width">
                            <div class="field center">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                    <path fill="#28a745" fill-rule="evenodd" d="M8 1.5a6.5 6.5 0 100 13 6.5 6.5 0 000-13zM0 8a8 8 0 1116 0A8 8 0 010 8zm9 3a1 1 0 11-2 0 1 1 0 012 0zm-.25-6.25a.75.75 0 00-1.5 0v3.5a.75.75 0 001.5 0v-3.5z"/>
                                </svg>
                                <span class="no-wrap">0 <small>open</small></span>
                            </div>
                            <div class="field center">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                    <path fill="#d73a49" fill-rule="evenodd" d="M1.5 8a6.5 6.5 0 0110.65-5.003.75.75 0 00.959-1.153 8 8 0 102.592 8.33.75.75 0 10-1.444-.407A6.5 6.5 0 011.5 8zM8 12a1 1 0 100-2 1 1 0 000 2zm0-8a.75.75 0 01.75.75v3.5a.75.75 0 11-1.5 0v-3.5A.75.75 0 018 4zm4.78 4.28l3-3a.75.75 0 00-1.06-1.06l-2.47 2.47-.97-.97a.749.749 0 10-1.06 1.06l1.5 1.5a.75.75 0 001.06 0z"/>
                                </svg>
                                <span class="no-wrap">0 <small>closed</small></span>
                            </div>
                        </div>
                    </section>
                    <section class="column">
                        <h3 class="no-margin-top">Pull requests</h3>
                        <svg class="bar" xmlns="http://www.w3.org/2000/svg" width="220" height="8">
                            <mask id="pr-bar">
                                <rect x="0" y="0" width="220" height="8" fill="white" rx="5"/>
                            </mask>
                            <rect mask="url(#pr-bar)" x="0" y="0" width="0" height="8" fill="#d1d5da"/>
                            <rect mask="url(#pr-bar)" x="0" y="0" width="0" height="8" fill="#28a745"/>
                            <rect mask="url(#pr-bar)" x="0" y="0" width="18.333333333333332" height="8" fill="#d73a49"/>
                            <rect mask="url(#pr-bar)" x="18.333333333333332" y="0" width="201.66666666666666" height="8" fill="#6f42c1"/>
                        </svg>
                        <div class="followup legend field horizontal fill-width">
                            <div class="field center">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                    <path fill="#28a745" fill-rule="evenodd" d="M7.177 3.073L9.573.677A.25.25 0 0110 .854v4.792a.25.25 0 01-.427.177L7.177 3.427a.25.25 0 010-.354zM3.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122v5.256a2.251 2.251 0 11-1.5 0V5.372A2.25 2.25 0 011.5 3.25zM11 2.5h-1V4h1a1 1 0 011 1v5.628a2.251 2.251 0 101.5 0V5A2.5 2.5 0 0011 2.5zm1 10.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.75 12a.75.75 0 100 1.5.75.75 0 000-1.5z"/>
                                </svg>
                                <span class="no-wrap">0 <small>open</small></span>
                            </div>
                            <div class="field center">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                    <path fill="#d73a49" fill-rule="evenodd" d="M10.72 1.227a.75.75 0 011.06 0l.97.97.97-.97a.75.75 0 111.06 1.061l-.97.97.97.97a.75.75 0 01-1.06 1.06l-.97-.97-.97.97a.75.75 0 11-1.06-1.06l.97-.97-.97-.97a.75.75 0 010-1.06zM12.75 6.5a.75.75 0 00-.75.75v3.378a2.251 2.251 0 101.5 0V7.25a.75.75 0 00-.75-.75zm0 5.5a.75.75 0 100 1.5.75.75 0 000-1.5zM2.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.25 1a2.25 2.25 0 00-.75 4.372v5.256a2.251 2.251 0 101.5 0V5.372A2.25 2.25 0 003.25 1zm0 11a.75.75 0 100 1.5.75.75 0 000-1.5z"/>
                                </svg>
                                <span class="no-wrap">1 <small>closed</small></span>
                            </div>
                            <div class="field center">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                    <path fill="#6f42c1" fill-rule="evenodd" d="M5 3.254V3.25v.005a.75.75 0 110-.005v.004zm.45 1.9a2.25 2.25 0 10-1.95.218v5.256a2.25 2.25 0 101.5 0V7.123A5.735 5.735 0 009.25 9h1.378a2.251 2.251 0 100-1.5H9.25a4.25 4.25 0 01-3.8-2.346zM12.75 9a.75.75 0 100-1.5.75.75 0 000 1.5zm-8.5 4.5a.75.75 0 100-1.5.75.75 0 000 1.5z"/>
                                </svg>
                                <span class="no-wrap">11 <small>merged</small></span>
                            </div>
                        </div>
                    </section>
                </div>
            </div>
            <section>
                <h2 class="field">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.5 2.75a.25.25 0 01.25-.25h12.5a.25.25 0 01.25.25v8.5a.25.25 0 01-.25.25h-6.5a.75.75 0 00-.53.22L4.5 14.44v-2.19a.75.75 0 00-.75-.75h-2a.25.25 0 01-.25-.25v-8.5zM1.75 1A1.75 1.75 0 000 2.75v8.5C0 12.216.784 13 1.75 13H3v1.543a1.457 1.457 0 002.487 1.03L8.061 13h6.189A1.75 1.75 0 0016 11.25v-8.5A1.75 1.75 0 0014.25 1H1.75zm5.03 3.47a.75.75 0 010 1.06L5.31 7l1.47 1.47a.75.75 0 01-1.06 1.06l-2-2a.75.75 0 010-1.06l2-2a.75.75 0 011.06 0zm2.44 0a.75.75 0 000 1.06L10.69 7 9.22 8.47a.75.75 0 001.06 1.06l2-2a.75.75 0 000-1.06l-2-2a.75.75 0 00-1.06 0z"/></svg>
      10 Languages
    </h2>
            </section>
            <section class="column">
                <h3 class="field">
        Most used languages
      </h3>
                <svg class="bar" xmlns="http://www.w3.org/2000/svg" width="460" height="8">
                    <mask id="languages-bar">
                        <rect x="0" y="0" width="460" height="8" fill="white" rx="5"/>
                    </mask>
                    <rect mask="url(#languages-bar)" x="0" y="0" width="0" height="8" fill="#d1d5da"/>
                    <rect mask="url(#languages-bar)" x="0" y="0" width="214.95752937664523" height="8" fill="#DA5B0B"/>
                    <rect mask="url(#languages-bar)" x="214.95752937664523" y="0" width="124.04264701891503" height="8" fill="#3572A5"/>
                    <rect mask="url(#languages-bar)" x="339.0001763955603" y="0" width="84.82065320632853" height="8" fill="#b07219"/>
                    <rect mask="url(#languages-bar)" x="423.8208296018888" y="0" width="13.187128551656762" height="8" fill="#e34c26"/>
                    <rect mask="url(#languages-bar)" x="437.0079581535456" y="0" width="9.008317729110695" height="8" fill="#563d7c"/>
                    <rect mask="url(#languages-bar)" x="446.0162758826563" y="0" width="8.611190262965074" height="8" fill="#f1e05a"/>
                    <rect mask="url(#languages-bar)" x="454.6274661456213" y="0" width="4.598564411517273" height="8" fill="#f34b7d"/>
                    <rect mask="url(#languages-bar)" x="459.2260305571386" y="0" width="0.7739694428614075" height="8" fill="#ffc200"/>
                </svg>
                <div class="field center horizontal-wrap fill-width">
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#DA5B0B" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                Jupyter Notebook
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#3572A5" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                Python
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#b07219" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                Java
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#e34c26" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                HTML
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#563d7c" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                CSS
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#f1e05a" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                JavaScript
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#f34b7d" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                C++
              </div>
                    <div class="field center no-wrap language">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill="#ffc200" fill-rule="evenodd" d="M8 4a4 4 0 100 8 4 4 0 000-8z"/></svg>
                Nim
              </div>
                </div>
            </section>
            <section>
                <h2 class="field">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M4.75 0a.75.75 0 01.75.75V2h5V.75a.75.75 0 011.5 0V2h1.25c.966 0 1.75.784 1.75 1.75v10.5A1.75 1.75 0 0113.25 16H2.75A1.75 1.75 0 011 14.25V3.75C1 2.784 1.784 2 2.75 2H4V.75A.75.75 0 014.75 0zm0 3.5h8.5a.25.25 0 01.25.25V6h-11V3.75a.25.25 0 01.25-.25h2zm-2.25 4v6.75c0 .138.112.25.25.25h10.5a.25.25 0 00.25-.25V7.5h-11z"/></svg>
      Contributions calendar
    </h2>
                <div class="row">
                    <section>
                    </section>
                    <section>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path d="M8.5.75a.75.75 0 00-1.5 0v5.19L4.391 3.33a.75.75 0 10-1.06 1.061L5.939 7H.75a.75.75 0 000 1.5h5.19l-2.61 2.609a.75.75 0 101.061 1.06L7 9.561v5.189a.75.75 0 001.5 0V9.56l2.609 2.61a.75.75 0 101.06-1.061L9.561 8.5h5.189a.75.75 0 000-1.5H9.56l2.61-2.609a.75.75 0 00-1.061-1.06L8.5 5.939V.75z"/></svg>
            Best streak 4 days
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M1.5 1.75a.75.75 0 00-1.5 0v12.5c0 .414.336.75.75.75h14.5a.75.75 0 000-1.5H1.5V1.75zm14.28 2.53a.75.75 0 00-1.06-1.06L10 7.94 7.53 5.47a.75.75 0 00-1.06 0L3.22 8.72a.75.75 0 001.06 1.06L7 7.06l2.47 2.47a.75.75 0 001.06 0l5.25-5.25z"/></svg>
            ~1.30 commits per day
          </div>
                    </section>
                </div>
                <svg version="1.1" xmlns="http://www.w3.org/2000/svg" style="margin-top: -52px;" viewBox="0,0 480,170">
                    <filter id="brightness1">
                        <feComponentTransfer>
                            <feFuncR type="linear" slope="0.6"/>
                            <feFuncG type="linear" slope="0.6"/>
                            <feFuncB type="linear" slope="0.6"/>
                        </feComponentTransfer>
                    </filter>
                    <filter id="brightness2">
                        <feComponentTransfer>
                            <feFuncR type="linear" slope="0.19999999999999996"/>
                            <feFuncG type="linear" slope="0.19999999999999996"/>
                            <feFuncB type="linear" slope="0.19999999999999996"/>
                        </feComponentTransfer>
                    </filter>
                    <g transform="scale(4) translate(12, 0)">
                        <g transform="translate(0, 0)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(1.7, 1)">
                            <g transform="translate(0, 5.793103448275862)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.793103448275862)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.793103448275862)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(3.4, 2)">
                            <g transform="translate(0, 5.793103448275862)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.896551724137931)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.689655172413794)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.310344827586207 0,1.3103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.3103448275862069 1.7,2.310344827586207 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(5.1, 3)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.689655172413794)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.310344827586207 0,1.3103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.3103448275862069 1.7,2.310344827586207 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(6.8, 4)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.482758620689655)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.5172413793103448 0,1.5172413793103448 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.5172413793103448 1.7,2.5172413793103448 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(8.5, 5)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.896551724137931)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.793103448275861)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(10.2, 6)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(11.9, 7)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.482758620689655)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.5172413793103448 0,1.5172413793103448 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.5172413793103448 1.7,2.5172413793103448 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(13.6, 8)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(15.299999999999999, 9)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.586206896551724)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.413793103448276 0,1.4137931034482758 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.4137931034482758 1.7,2.413793103448276 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.793103448275861)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(17, 10)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.689655172413794)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.310344827586207 0,1.3103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.3103448275862069 1.7,2.310344827586207 z"/>
                            </g>
                            <g transform="translate(-3.4, 6.241379310344827)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.758620689655172 0,2.758620689655172 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.758620689655172 1.7,3.758620689655172 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.793103448275861)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.586206896551724)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.413793103448276 0,1.4137931034482758 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.4137931034482758 1.7,2.413793103448276 z"/>
                            </g>
                        </g>
                        <g transform="translate(18.7, 11)">
                            <g transform="translate(0, 4.137931034482759)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.8620689655172415 0,2.8620689655172415 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.8620689655172415 1.7,3.8620689655172415 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 6.758620689655173)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.2413793103448274 0,2.2413793103448274 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.2413793103448274 1.7,3.2413793103448274 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-8.5, 9.862068965517242)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.1379310344827585 0,2.1379310344827585 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.1379310344827585 1.7,3.1379310344827585 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.793103448275861)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                        </g>
                        <g transform="translate(20.4, 12)">
                            <g transform="translate(0, 0)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,8 0,7 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,7 1.7,8 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.896551724137931)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.793103448275861)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.793103448275861)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(22.099999999999998, 13)">
                            <g transform="translate(0, 5.379310344827586)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.6206896551724137 0,1.6206896551724137 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.6206896551724137 1.7,2.6206896551724137 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(23.8, 14)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(25.5, 15)">
                            <g transform="translate(0, 5.896551724137931)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.793103448275861)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.172413793103448)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.8275862068965516 0,1.8275862068965516 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.8275862068965516 1.7,2.8275862068965516 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                        </g>
                        <g transform="translate(27.2, 16)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.896551724137931)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.793103448275861)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                        </g>
                        <g transform="translate(28.9, 17)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.689655172413794)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.310344827586207 0,1.3103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.3103448275862069 1.7,2.310344827586207 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.689655172413794)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.310344827586207 0,1.3103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.3103448275862069 1.7,2.310344827586207 z"/>
                            </g>
                            <g transform="translate(-8.5, 9.96551724137931)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.0344827586206895 0,2.0344827586206895 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.0344827586206895 1.7,3.0344827586206895 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(30.599999999999998, 18)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.689655172413794)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.310344827586207 0,1.3103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.3103448275862069 1.7,2.310344827586207 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                        </g>
                        <g transform="translate(32.3, 19)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.482758620689655)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.5172413793103448 0,1.5172413793103448 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.5172413793103448 1.7,2.5172413793103448 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.793103448275861)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(34, 20)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.793103448275861)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.206896551724138 0,1.206896551724138 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.206896551724138 1.7,2.206896551724138 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(35.699999999999996, 21)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(37.4, 22)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.896551724137931)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.89655172413793)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(39.1, 23)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(40.8, 24)">
                            <g transform="translate(0, 5.896551724137931)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.586206896551724)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.413793103448276 0,1.4137931034482758 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.4137931034482758 1.7,2.413793103448276 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.379310344827587)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.6206896551724137 0,1.6206896551724137 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.6206896551724137 1.7,2.6206896551724137 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(42.5, 25)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(44.199999999999996, 26)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.896551724137931)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.103448275862069 0,1.103448275862069 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.103448275862069 1.7,2.103448275862069 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                    </g>
                </svg>
            </section>
            <section>
                <h2 class="field">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M0 8a8 8 0 1116 0v5.25a.75.75 0 01-1.5 0V8a6.5 6.5 0 10-13 0v5.25a.75.75 0 01-1.5 0V8zm5.5 4.25a.75.75 0 01.75-.75h3.5a.75.75 0 010 1.5h-3.5a.75.75 0 01-.75-.75zM3 6.75C3 5.784 3.784 5 4.75 5h6.5c.966 0 1.75.784 1.75 1.75v1.5A1.75 1.75 0 0111.25 10h-6.5A1.75 1.75 0 013 8.25v-1.5zm1.47-.53a.75.75 0 011.06 0l.97.97.97-.97a.75.75 0 011.06 0l.97.97.97-.97a.75.75 0 111.06 1.06l-1.5 1.5a.75.75 0 01-1.06 0L8 7.81l-.97.97a.75.75 0 01-1.06 0l-1.5-1.5a.75.75 0 010-1.06z"/></svg>
      Recent activity
    </h2>
                <div class="row">
                    <section>
                        <div class="row fill-width">
                            <section class="activity">
                                <div class="field">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                        <path fill-rule="evenodd" d="M10.5 7.75a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0zm1.43.75a4.002 4.002 0 01-7.86 0H.75a.75.75 0 110-1.5h3.32a4.001 4.001 0 017.86 0h3.32a.75.75 0 110 1.5h-3.32z"/>
                                    </svg>
                                    <div class="content">
                      Pushed 1 commit in <span class="repo">s-tyda/Design-Patterns-Challenge</span>
                    </div>
                                </div>
                                <div class="details">
                                    <div>on branch <span class="code">master</span></div>
                                    <div class="commit">
                                        <span class="sha">#15e165a</span>
                                        <span class="message">Added readme files for every catalog</span>
                                    </div>
                                </div>
                                <div class="timestamp">
                    18/06/2021, 03:08
                  </div>
                            </section>
                        </div>
                        <div class="row fill-width">
                            <section class="activity">
                                <div class="field">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                        <path fill-rule="evenodd" d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"/>
                                    </svg>
                                    <div class="content">
                      Forked <span class="repo">zipoz89/23DesignPatternsIn23DaysInUnity</span> to <span class="repo">s-tyda/23DesignPatternsIn23DaysInUnity</span>
                    </div>
                                </div>
                                <div class="timestamp">
                    18/06/2021, 03:06
                  </div>
                            </section>
                        </div>
                        <div class="row fill-width">
                            <section class="activity">
                                <div class="field">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                        <path fill-rule="evenodd" d="M10.5 7.75a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0zm1.43.75a4.002 4.002 0 01-7.86 0H.75a.75.75 0 110-1.5h3.32a4.001 4.001 0 017.86 0h3.32a.75.75 0 110 1.5h-3.32z"/>
                                    </svg>
                                    <div class="content">
                      Pushed 1 commit in <span class="repo">s-tyda/Design-Patterns-Challenge</span>
                    </div>
                                </div>
                                <div class="details">
                                    <div>on branch <span class="code">master</span></div>
                                    <div class="commit">
                                        <span class="sha">#70e2fce</span>
                                        <span class="message">Updated .gitignore</span>
                                    </div>
                                </div>
                                <div class="timestamp">
                    18/06/2021, 03:00
                  </div>
                            </section>
                        </div>
                        <div class="row fill-width">
                            <section class="activity">
                                <div class="field">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                        <path fill-rule="evenodd" d="M10.5 7.75a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0zm1.43.75a4.002 4.002 0 01-7.86 0H.75a.75.75 0 110-1.5h3.32a4.001 4.001 0 017.86 0h3.32a.75.75 0 110 1.5h-3.32z"/>
                                    </svg>
                                    <div class="content">
                      Pushed 1 commit in <span class="repo">s-tyda/Design-Patterns-Challenge</span>
                    </div>
                                </div>
                                <div class="details">
                                    <div>on branch <span class="code">master</span></div>
                                    <div class="commit">
                                        <span class="sha">#1b7ac0f</span>
                                        <span class="message">Added .gitignore</span>
                                    </div>
                                </div>
                                <div class="timestamp">
                    18/06/2021, 03:00
                  </div>
                            </section>
                        </div>
                        <div class="row fill-width">
                            <section class="activity">
                                <div class="field">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
                                        <path fill-rule="evenodd" d="M10.5 7.75a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0zm1.43.75a4.002 4.002 0 01-7.86 0H.75a.75.75 0 110-1.5h3.32a4.001 4.001 0 017.86 0h3.32a.75.75 0 110 1.5h-3.32z"/>
                                    </svg>
                                    <div class="content">
                      Pushed 1 commit in <span class="repo">s-tyda/Design-Patterns-Challenge</span>
                    </div>
                                </div>
                                <div class="details">
                                    <div>on branch <span class="code">master</span></div>
                                    <div class="commit">
                                        <span class="sha">#5f7efe6</span>
                                        <span class="message">Added new design pattern - singleton</span>
                                    </div>
                                </div>
                                <div class="timestamp">
                    18/06/2021, 02:58
                  </div>
                            </section>
                        </div>
                    </section>
                </div>
            </section>
            <footer>
                <span>These metrics do not include all private contributions</span>
                <span>Last updated Thu, 01 Jul 2021 02:54:55 (timezone Europe/Warsaw) with lowlighter/metrics@3.10.0</span>
            </footer>
            <div id="metrics-end"></div>
        </div>
    </foreignObject>
</svg>
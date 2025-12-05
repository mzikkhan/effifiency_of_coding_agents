# What Affects the Efficiency of Coding Agents?

With the rapid evolution of software engineering, the integration of autonomous coding agents are becoming a larger part of our software workflows. This github repository explores the efficiency of coding agents and what affects the efficiency.
All the analyses in this report and repository are drawn from the AIDev dataset introduced by Li et al. (2025), which provides a large-scale empirical data on how autonomous coding agenst operate across more than 456000 pull requests authored  by major agentic systems such as Codex, Devin, GitHub Copilot, Cursor and Caude Code.

To evaluate the effciency, we used two distinct measures. (1) The elapsed time from PR creation to PR closing, and (2) the nunmber of iteration cycles involved, including commits, reviews and request changes.

Next we examined the reviwer type, human, bot or a hybrid of both influences the efficiency of the AI generated pul requests.

Finally, we investigate how review feedback tone (poistive, neural, negative) impacts PR effciency based on our measures from before.

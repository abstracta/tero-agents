# Tero Community Agents

This is the open community repository for [Tero](https://github.com/abstracta/tero) agents.

Here you can find a curated set of agents contributed by the community that you can use in your Tero instance, and you can contribute your own agents as well.

See the index of contributed agents in [`index.md`](index.md).

> Important: The maintainers of this repository will do basic checks before accepting contributions but will not fully test agents for functionality or quality. You are responsible for reviewing agents and ensuring they fit your needs.
>
> Tip: Check the agent author as a quality signal. For example, agents authored by Abstracta have been validated and properly tested by Abstracta.


## Using agents

1. Browse the agent list in [`index.md`](index.md) and pick an agent.
2. Clone this repository or download it as a ZIP from GitHub.
 > If you clone the repository make sure you have git-lfs support installed.
 >
 > To get the ZIP with all necessary files from GitHub, you need to right click the ZIP link and select "Save link as ...". This is necessary due to [this GitHub open issue](https://github.com/git-lfs/git-lfs/issues/903#issuecomment-632841480).
3. Zip only the folder of the agent you want to use.
4. In your Tero instance, create a new agent and import the ZIP.
5. Check if the agent requires additional configuration (eg: Jira or MCP credentials) and test it.


## Contributing agents

To contribute an agent you have in your Tero instance:

1. Ensure your agent has a clear and descriptive name, description and icon.
2. Remove any private prompts you don't want to contribute.
3. Export your agent from Tero and unzip the exported file.
4. Fork this repository.
5. Add your agent folder to the appropriate language directory:
   - English: `./en`
   - Spanish: `./es`
   - Other languages: create a new directory named with the proper language code (ISO 639‑1).
6. Open a pull request from your fork to this repository.


## Questions and support

- For issues with a specific agent, please open an issue describing:
  - Agent name and language folder
  - Expected behavior vs. actual behavior
  - Repro steps and environment details
- For general questions about Tero, see the main project: https://github.com/abstracta/tero

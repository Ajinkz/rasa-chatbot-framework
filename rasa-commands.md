### To start new project 
- `rasa init`

### To train model
- `rasa train`

### To test the bot in cmd
- `rasa shell`

### To test bot with web socket/api
- `rasa run --cors "*" --debug --enable-api`

### list of all possible commands

| Command               | Effect                                                                                           |
|-----------------------|--------------------------------------------------------------------------------------------------|
| `rasa init`             | Creates a new project with example training data, actions, and config files.                     |
| `rasa train`            | Trains a model using your NLU data and stories, saves trained model in ./models.                 |
| `rasa interactive`      | Starts an interactive learning session to create new training data by chatting.                  |
| `rasa shell`            | Loads your trained model and lets you talk to your assistant on the command line.                |
| `rasa run`              | Starts a Rasa server with your trained model. See the Configuring the HTTP API docs for details. |
| `rasa run actions`      | Starts an action server using the Rasa SDK.                                                      |
| `rasa visualize`        | Visualizes stories.                                                                              |
| `rasa test`             | Tests a trained Rasa model using your test NLU data and stories.                                 |
| `rasa data split nlu`   | Performs a split of your NLU data according to the specified percentages.                        |
| `rasa data convert nlu` | Converts NLU training data between different formats.                                            |
| `rasa export`           | Export conversations from a tracker store to an event broker.                                    |
| `rasa x`                | Launch Rasa X locally.                                                                           |
| `rasa -h`               | Shows all available commands.                                                                    |

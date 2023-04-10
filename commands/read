const { SlashCommandBuilder } = require("discord.js");

module.exports = {
  data: new SlashCommandBuilder()
    .setName("read")
    .setDescription("Does a Yi Jing reading."),
  async execute(interaction) {
    await interaction.reply(
      `This command was run by ${interaction.user.username}, who joined on ${interaction.member.joinedAt}.`
    );
  },
};

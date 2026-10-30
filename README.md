# claude-rules

Collection on system prompts for Claude Code.

Simple start (+/-):

Clone this project to `~/work/claude-rules`

```
mkdir -p ~/.claude/rules
ln -s ../../work/claude-rules/general ~/.claude/rules/
```

To check if rules are working, prompt Claude to do this:
```
Create sample.sh which creates temporary file and puts "hello world" into it.
```

It should create script which will contain cleanup() as specified in [general/code-style.md](general/code-style.md).

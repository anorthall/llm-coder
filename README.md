# llm-coder
A utility to copy multiple files into an LLM prompt to ask questions about them.

## Usage
1. Download `llm-coder`, which is a Python script, and insert it into your system path.
2. Run the `llm-coder` script and provide a list of files you wish to be summarised in a
   prompt as arguments to the command.
3. The resulting prompt will be copied to your clipboard.

## Token Counter
If [tiktoken](https://github.com/openai/tiktoken) is installed, a token count for the generated
prompt will be shown after script execution. If tiktoken is not installed, this feature will
not be enabled.

## Requirements
On Mac OS X, this script has no requirements other than Python. On other platforms, you
will need to install `pyperclip` to enable copying to the clipboard.

[tiktoken](https://github.com/openai/tiktoken) must be installed to enable token counting.

## Licence
Licenced under the MIT Licence.

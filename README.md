# fileagent

A simple `cli` file AI agent built with `Golang` and `Anthropic API`. It can:
- Read files
- Edit files
- List files and directories
- Delete files

## Requirements
- Go 1.24 or later
- Anthropic API key

## Installation
1. Clone the repository:
   ```bash
   git clone
    cd fileagent
    ```
2. Install dependencies:
    ```bash
    go mod tidy
    ```
3. Create a `.env` file in the root directory and add your Anthropic API key:
    ```env
    ANTHROPIC_API_KEY=your_anthropic_api_key
    ```
   Replace `your_anthropic_api_key` with your actual API key.
  
4. Run the application:
    ```bash
    go run main.go
    ```
# AI SDK Python Streaming Preview

This template demonstrates the usage of [Data Stream Protocol](https://sdk.vercel.ai/docs/ai-sdk-ui/stream-protocol#data-stream-protocol) to stream chat completions from a Python endpoint ([FastAPI](https://fastapi.tiangolo.com)) and display them using the [useChat](https://sdk.vercel.ai/docs/ai-sdk-ui/chatbot#chatbot) hook in your Next.js application.

## Deploy your own

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel-labs/ai-sdk-preview-python-streaming)

## How to use

To run the example locally you need to:

1. Set the required environment variables as shown in the `.env.example` file, but in a new file called `.env`.
2. `pnpm install` to install the required Node dependencies.
3. `virtualenv venv` to create a virtual environment.
4. `source venv/bin/activate` to activate the virtual environment.
5. `pip install -r requirements.txt` to install the required Python dependencies.
6. `pnpm dev` to launch the development server.

## Learn More

To learn more about the AI SDK or Next.js by Vercel, take a look at the following resources:

- [AI SDK Documentation](https://sdk.vercel.ai/docs)
- [Next.js Documentation](https://nextjs.org/docs)

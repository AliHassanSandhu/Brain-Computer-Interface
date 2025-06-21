# Brain Computer Interface

## Backend Description



### Requirements
- Python 3.x
- Uvicorn
- FastAPI (or any other framework you are using)

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/umertariq22/BCI-Backend.git
    cd yourproject
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Project
To run the project using Uvicorn, use the following command:
```bash
uvicorn main:app --reload
```
Replace `main:app` with the appropriate module and application instance name.

### Configuration
- `--reload`: Enables auto-reload for development.
- `--host`: Specify the host, default is `127.0.0.1`.
- `--port`: Specify the port, default is `8000`.

Example:
```bash
uvicorn main:app --reload --host 0.0.0.0 --port 8000
```
## Frontend Description

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

### Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

### Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

### Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.
Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

# License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

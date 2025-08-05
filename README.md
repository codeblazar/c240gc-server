# C240GC Server

An AI stack server setup with n8n workflow automation and Flowise AI flows, backed by PostgreSQL.

## Services

- **n8n**: Workflow automation platform
- **Flowise**: Low-code AI app builder 
- **PostgreSQL**: Database backend

## Quick Start

1. Clone this repository:
   ```bash
   git clone https://github.com/codeblazar/c240gc-server.git
   cd c240gc-server
   ```

2. Copy the environment template and configure:
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

3. Start the services:
   ```bash
   docker-compose up -d
   ```

## Services Access

- **n8n**: https://n8ngc.codeblazar.org (or localhost:5678)
- **Flowise**: localhost:3000

## Environment Configuration

See `.env.example` for required environment variables.

## Custom Nodes

Place custom n8n nodes in the `custom-nodes/` directory.

## Security Notes

- Change default passwords in `.env` before deployment
- Use strong authentication credentials
- Configure proper firewall rules for production

## License

MIT License

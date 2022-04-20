# polka_scripts

Usage: ./update_node <version> (without the v in version). Example: ./update_node 0.9.8
polkadot: User running the service (change accordingly in chown polkadot:polkadot)
polkadot.service: Service name (change accordingly in all instances)
The last line journalctl will run the service logs to check the update has been successful. Exit with Ctrl+C

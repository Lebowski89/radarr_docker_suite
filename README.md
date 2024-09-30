Radarr Suite
=========

    Ansible role to automate the full set-up of Radarr - a movie collection manager for Usenet and BitTorrent users.
      - Includes the installation of Docker (Debian-based distros) and Ansible dependencies within the role.
      - Includes the option of setting up and connecting Radarr to a Postgres database.
      - Includes the option of setting up Prometheus and a Radarr Promtheus exporter to gather various metrics about your Radarr usage and music collection.
      - Includes the option of creating a Cloudflare DNS record for your Radarr instance for reverse proxy purposes.
      - Includes the option of setting up Autofs NFS (to provide media access on the host system) and Docker NFS volumes (to attach to the Radarr container).
      - Includes the option of setting up the Rclone Docker plugin and the creation of Rclone Docker volumes (to attach to the Radarr container).
      - Includes the option of joining Radarr to an existing Traefik docker network (or creating one if none exists).
      - Includes the option of editing Radarr's config.xml to include an existing Radarr API - maintaining connections to other applications that rely on it.

(Proper documentation is coming...)
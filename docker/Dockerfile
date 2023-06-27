# 5GB image/may be too big as an image
FROM cm2network/steamcmd:steam

USER steam
RUN /home/steam/steamcmd/steamcmd.sh +force_install_dir /home/steam/zomboid_ds +login anonymous +app_update 380870 +quit
CMD bash /home/steam/zomboid_ds/start-server.sh
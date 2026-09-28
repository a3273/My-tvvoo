FROM qwertyuiop8899/tvvoo:latest

# Beamup ascolta su 7860 di default (vedi log: "port listening check" port=7860)
# Non cambiare a 7860/8000/10000 su beamup — causerà healthcheck failure
ENV PORT=7860
EXPOSE 7860
CMD ["node", "dist/addon.js"]

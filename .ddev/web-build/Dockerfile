ARG BASE_IMAGE
FROM $BASE_IMAGE

ENV NVM_DIR=/usr/local/nvm

# Install NVM.
RUN curl -sL https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh -o install_nvm.sh
RUN mkdir -p $NVM_DIR && bash install_nvm.sh
RUN echo "source $NVM_DIR/nvm.sh" >>/etc/profile
RUN chmod -R ugo+w $NVM_DIR


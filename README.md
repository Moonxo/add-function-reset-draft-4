# add-function-reset-draft-4
function resetMyGarage() external override {
        delete garages[msg.sender];
    }

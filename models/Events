const mongoose = require("mongoose")


const EventSchema = new mongoose.Schema(
    {
        userId: {
            type: String,
            required: true 
        },
        eventId: {
            type: String,
            required: true 
        },
        desc: {
            type: String,
            max: 500
        },
        img: {
            type: String
        },
        attending: {
            type: Array,
            default: [],

        },
        interested: {
            type: Array,
            default: [],
        },
        date: {
            type: Date,
            default: [],
        },
        location: {
            type: String,
            default: [],
        }
    
    }, 
 { timestamps:true }
);

module.exports = mongoose.model("Event", EventSchema)
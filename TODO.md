# TODO LIST

### Urgent
- [ ] Check for duplicate vouchers
- [ ] Vouching cooldowns
- [ ] Dockerize project for deployment

### Features
- [ ] Extra tags i.e. Scammer, whale, etc.
- [ ] Better project layout


Vouching cooldowns:
- cooldown for receiving and giving?
- two columns, last_given, last_received
- check last_given when giving vouch and if time delta > 1 hr, return
- last_received same idea (maybe not good to have a received cooldown)
# solid-guide
-- Riders
INSERT INTO Riders (RiderID, RiderName, Team, Age)
VALUES
(1, 'Marc Marquez', 'Repsol Honda', 29),
(2, 'Fabio Quartararo', 'Yamaha', 23),
(3, 'Francesco Bagnaia', 'Ducati', 25),
(4, 'Joan Mir', 'Suzuki', 24);

-- Bikes
INSERT INTO Bikes (BikeID, Model, TopSpeed)
VALUES
(1, 'Honda RC213V', 350),
(2, 'Yamaha YZR-M1', 345),
(3, 'Ducati Desmosedici', 355),
(4, 'Suzuki GSX-RR', 340);

-- Races
INSERT INTO Races (RaceID, RaceName, Location, RaceDate)
VALUES
(1, 'Qatar GP', 'Losail', '2026-03-05'),
(2, 'Spain GP', 'Jerez', '2026-05-01'),
(3, 'Italy GP', 'Mugello', '2026-06-12'),
(4, 'France GP', 'Le Mans', '2026-05-20');

-- Race Results
INSERT INTO RaceResults (ResultID, RiderID, BikeID, RaceID, Position, Points)
VALUES
(1, 1, 1, 1, 1, 25),
(2, 2, 2, 1, 2, 20),
(3, 3, 3, 1, 3, 16),
(4, 4, 4, 1, 4, 13),
(5, 1, 1, 2, 2, 20),
(6, 2, 2, 2, 1, 25),
(7, 3, 3, 2, 4, 13),
(8, 4, 4, 2, 3, 16),
(9, 1, 1, 3, 3, 16),
(10, 2, 2, 3, 4, 13),
(11, 3, 3, 3, 1, 25),
(12, 4, 4, 3, 2, 20),
(13, 1, 1, 4, 1, 25),
(14, 2, 2, 4, 3, 16),
(15, 3, 3, 4, 2, 20),
(16, 4, 4, 4, 4, 13);

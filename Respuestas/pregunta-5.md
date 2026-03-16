db.libros.aggregate([{ $group: { _id: "$categoria", total: { $sum: 1 } } }])

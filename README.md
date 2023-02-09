# Iterating-maps

const map = new Map([[1, 2], [3, 4]]);
for (const [key, value] of map) {
 console.log(`key: ${key}, value: ${value}`);
 // logs:
 // key: 1, value: 2
 // key: 3, value: 4
}
for (const key of map.keys()) {
 console.log(key); // logs 1 and 3
}
for (const value of map.values()) {
 console.log(value); // logs 2 and 4
}

/**
 * @param {integer} init
 * @return {{decrement: (function(): integer), increment: (function(): integer), reset: (function(): integer)}}
 */
var createCounter = function(init) {
    let value = init

    let increment = () => {
        value++
        return value
    }

    let reset = () => {
        value = init
        return value
    }
    let decrement = () => {
        value--
        return value
    }

    return {
        increment, decrement, reset
    }
};

/**
 * const counter = createCounter(5)
 * counter.increment(); // 6
 * counter.reset(); // 5
 * counter.decrement(); // 4
 */

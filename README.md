"# useSearchParam-react-hook"

Use the useCallback() hook to create a callback that uses the URLSearchParams constructor to get the current value of param.
Use the useState() hook to create a state variable that holds the current value of the param.
Use the useEffect() hook to set appropriate event listeners to update the state variable when mounting and clean them up when unmounting.
const useSearchParam = param => {
